pipeline {
   agent {
     label 'windows'
}
def PowerShell(psCmd) {
    psCmd=psCmd.replaceAll("%", "%%")
    bat "powershell.exe -NonInteractive -ExecutionPolicy Bypass -Command \"\$ErrorActionPreference='Stop';[Console]::OutputEncoding=[System.Text.Encoding]::UTF8;$psCmd;EXIT \$global:LastExitCode\""
}
  stages {
    stage('hello') {
      steps {
        PowerShell(". '.\\hello.ps1'") 
      }
    }
  }
}

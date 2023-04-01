pipeline {
   agent {
     label 'windows'
}
 stages {
    stage('hello') {
      steps {
        PowerShell(". '.\\hello.ps1'") 
      }
    }
  }
}

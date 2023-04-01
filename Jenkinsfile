pipeline {
   agent {
     label 'windows'
}
  stages {
    stage('version') {
      steps {
        bat 'powershell "C:\jenkins-agent\workspace\mypipe\hello.ps1"'
      }
    }
  }
}




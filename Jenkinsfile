pipeline {
   agent {
     label 'windows'
}
  stages {
    stage('version') {
      steps {
        bat 'powershell "hostname"'
      }
    }
  }
}


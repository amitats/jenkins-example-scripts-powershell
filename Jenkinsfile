pipeline {
   agent {
     label 'windows'
}
  stages {
    stage('version') {
      steps {
        sh 'pwsh --version'
      }
    }
    stage('hello') {
      steps {
        sh 'pwsh hello.ps1'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('verify make is installed') {
      steps {
        sh 'make --version'
      }
    }
    stage('run hello target') {
      steps {
        sh 'make'
      }
    }
  }
}
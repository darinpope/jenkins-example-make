pipeline {
  agent any
  stages {
    stage('verify make is installed') {
      steps {
        sh 'make --version'
      }
    }
    stage('run make') {
      steps {
        sh 'make'
      }
    }
  }
}

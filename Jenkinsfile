pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }
  }
  stages {
    stage('Test stage') {
      steps {
        echo 'Welcome to Donamus!'
        sh 'mvn --version '
      }
    }
  }
}
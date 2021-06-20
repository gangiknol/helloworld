pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'checkout'
      }
    }

    stage('build') {
      steps {
        sh 'echo "build"'
      }
    }

    stage('') {
      steps {
        sh 'echo "deploy"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test url"'
      }
    }

  }
  environment {
    a = '10'
    b = '20'
    c = '30'
  }
}
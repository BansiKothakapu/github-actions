pipeline {
  agent any

  stages {
    stage('Check Out') {
      steps {
        sh 'https://github.com/BansiKothakapu/github-actions.git'
      }
    }

    stage('Build') {
      steps {
        echo 'Executing Build Phase')
      }
    }

    stage('Testing') {
      steps {
        echo 'Executing Testing Phase')
      }
    }

    stage('Deploying') {
      steps {
        echo 'Executing Deployment Phase')
      }
    }
  }
}

pipeline {
  agent any

  stages {
    stage('Check Out') {
      steps {
        sh 'git clone https://github.com/BansiKothakapu/github-actions.git'
      }
    }

    stage('Build') {
      steps {
        echo 'This is the Executing Build Phase.....'
      }
    }

    stage('Testing') {
      steps {
        echo 'Executing Testing Phase'
      }
    }

   stage('Static Code Analaysis') {
      steps {
         echo 'Executing SCA phase'
       }       

   }

    stage('Report') {
      steps {
        echo 'Sending Report to Sonar Server'
      }
    }
    stage('Deploying') {
      steps {
        echo 'Executing Deployments Phase'
      }
    }
  }
}

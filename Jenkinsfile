pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''ls
pwd'''
      }
    }

    stage('Build') {
      steps {
        echo 'yes build'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploy on test'
        sleep 10
      }
    }

    stage('Prod') {
      steps {
        echo 'deploy on prod'
      }
    }

  }
}
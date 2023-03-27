pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Hello there'
          }
        }

        stage('Test par') {
          steps {
            echo 'GXI'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'My name is tanya'
        sleep 10
      }
    }

  }
}
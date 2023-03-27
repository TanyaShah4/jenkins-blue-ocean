pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
cal 2023
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

        stage('Test1') {
          steps {
            echo 'wow'
          }
        }

      }
    }

    stage('Deploy') {
      parallel {
        stage('Deploy') {
          steps {
            echo 'My name is tanya'
          }
        }

        stage('Deploy2') {
          steps {
            echo 'Deploy to production'
          }
        }

      }
    }

  }
}
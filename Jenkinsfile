pipeline {
  agent any
  stages {
    stage('Hello World') {
      parallel {
        stage('Hello World') {
          steps {
            echo 'Hello World!'
          }
        }

        stage('nvidia-smi') {
          steps {
            sh 'nvidia-smi'
          }
        }

      }
    }

  }
}
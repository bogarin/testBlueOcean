pipeline {
  agent any
  stages {
    stage('hola') {
      parallel {
        stage('hola') {
          steps {
            echo 'hola como estan'
          }
        }

        stage('test-pipeline') {
          steps {
            echo 'dos'
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'jiluil'
      }
    }

  }
}
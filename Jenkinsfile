pipeline {
  agent any
  stages {
    stage('message') {
      steps {
        echo 'hello word'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'unit'
          }
        }

        stage('test2') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('deploiement') {
      steps {
        echo 'deploiement'
      }
    }

  }
}
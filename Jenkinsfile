pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build Complited'
          }
        }

        stage('Test') {
          steps {
            echo 'test'
            echo 'Test'
          }
        }

      }
    }

    stage('clean') {
      steps {
        echo 'done'
      }
    }

  }
}
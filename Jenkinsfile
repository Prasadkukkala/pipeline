pipeline {
  agent any
  stages {
    stage('commit') {
      steps {
        echo 'commit the message'
      }
    }

    stage('Build') {
      steps {
        echo 'Build the message'
      }
    }

    stage('Test ') {
      parallel {
        stage('Test ') {
          steps {
            echo 'Test the message'
          }
        }

        stage('Test 1') {
          steps {
            echo 'Test 1 the message'
          }
        }

      }
    }

    stage('End') {
      steps {
        echo 'End message'
      }
    }

  }
}
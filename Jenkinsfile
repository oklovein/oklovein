pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building..'
          }
        }
        stage('Stage1') {
          steps {
            echo 'Hi'
          }
        }
        stage('Stage 2') {
          steps {
            echo 'Hello Message'
            echo '2nd Mnesage'
          }
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
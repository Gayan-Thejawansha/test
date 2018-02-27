pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build the project'
          }
        }
        stage('Build 2') {
          steps {
            echo 'Done'
          }
        }
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'test starts'
          }
        }
        stage('further testing') {
          steps {
            echo 'tested'
          }
        }
      }
    }
    stage('intrgt') {
      steps {
        echo 'Print smthing'
      }
    }
  }
}

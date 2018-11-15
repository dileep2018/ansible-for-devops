pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "date"'
          }
        }
        stage('checkout') {
          steps {
            sh 'echo time'
          }
        }
        stage('you') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('hi') {
      parallel {
        stage('hi') {
          steps {
            sleep 5
          }
        }
        stage('wq') {
          steps {
            ws(dir: 'ws') {
              sh 'mkdir tab'
            }

          }
        }
      }
    }
  }
  environment {
    name = 'java'
  }
}
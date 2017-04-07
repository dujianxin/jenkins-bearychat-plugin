pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd'
      }
    }
    stage('Test') {
      steps {
        sh 'echo TEST'
      }
    }
    stage('') {
      steps {
        waitUntil() {
          echo 'aaa'
        }
        
      }
    }
  }
}
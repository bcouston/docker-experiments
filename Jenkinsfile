pipeline {
  agent any
  stages {
    stage('Manual check') {
      steps {
        input 'Approve?'
      }
    }
    stage('Stage 2') {
      steps {
        sh 'pwd'
      }
    }
  }
}
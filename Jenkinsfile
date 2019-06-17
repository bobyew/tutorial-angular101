pipeline {
  agent any
  stages {
    stage('sleep 1') {
      steps {
        sleep 10
      }
    }
    stage('echo') {
      steps {
        bat(script: 'echo xxxx', returnStatus: true, label: 'yyy')
      }
    }
    stage('') {
      steps {
        sleep 5
      }
    }
  }
}
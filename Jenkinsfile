pipeline {
  agent {
    node {
      label 'RCTUbtSlave01'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo 1'
      }
    }
    stage('Test') {
      steps {
        sh 'echo test1'
      }
    }
  }
}
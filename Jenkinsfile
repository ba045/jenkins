pipeline {
  agent any
  stages {
    stage('blue') {
      steps {
        sh 'sh test.sh'
      }
    }

  }
  environment {
    stage = 'test'
  }
}
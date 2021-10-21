pipeline {
  agent any
  stages {
    stage('blue') {
      parallel {
        stage('blue') {
          steps {
            sh 'sh test.sh'
          }
        }

        stage('test2') {
          steps {
            sh 'echo "hello~"'
          }
        }

      }
    }

  }
  environment {
    stage = 'test'
  }
}
pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "Hello from Stage1"'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "Hello from Stage2"'
          }
        }

      }
    }

  }
}
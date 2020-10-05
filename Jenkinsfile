pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'hello test message'
          }
        }

        stage('test') {
          steps {
            echo 'test message'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'build message '
      }
    }

  }
}
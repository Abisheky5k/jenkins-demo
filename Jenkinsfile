pipeline {
  agent {
    docker {
      image 'centos:latest'
    }

  }
  stages {
    stage('maven build') {
      steps {
        sh 'mvn clean'
      }
    }

  }
}
pipeline {
  agent {
    docker {
      image 'centos:latest'
      args 'mvn clean'
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
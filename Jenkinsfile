pipeline {
  agent {
    docker {
      image 'centos:3.6.3-openjdk-16'
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
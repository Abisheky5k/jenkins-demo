pipeline {
  agent {
    docker {
      args 'mvn clean'
      image 'openjdk:11-jdk'
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
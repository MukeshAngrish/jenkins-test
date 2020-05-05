pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/saraivamarco/spring-rest-example/'
      }
    }

    stage('Build') {
      steps {
        sh 'mvn clean test compile package'
      }
    }

  }
}
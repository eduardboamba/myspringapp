pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './mvnw clean install -DskipTests'
      }
    }

    stage('Test') {
      steps {
        sh './mvnw test'
      }
    }

  }
}
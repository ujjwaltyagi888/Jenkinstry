pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "running ${env.BUILD_ID} on ${env.BUILD_URL}"
        sleep 5
      }
    }
    stage('Test') {
      steps {
        echo "testing"
        sleep 10
      }
    }
    stage('Deploy') {
      steps {
        echo "deploying"
        stageMessage "sample stage message"
      }
    }
  }
}
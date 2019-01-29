pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
    stage('Build Release') {
      steps {
        echo "Build Release"
        sleep 60
      }
    }
    stage('Promote to Environments') {
      steps {
        echo "Promote to Environments"
        sleep 60
      }
    }
  }
}

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
      }
    }
    stage('Promote to Environments') {
      steps {
        echo "Promote to Environments"
      }
    }
  }
}

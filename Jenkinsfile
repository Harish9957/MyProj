pipeline {
  agent any
  stages {
    stage('Git Checkout the Code') {
      steps {
        echo 'Git clone the repo'
      }
    }

    stage('Build') {
      steps {
        echo 'Build the Appl & generate the artifacts'
      }
    }

    stage('Unit Tests') {
      steps {
        echo 'Test your App'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy your App from main branch'
      }
    }

  }
}

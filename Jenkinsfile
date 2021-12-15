pipeline {
    agent any
    stages{
    stage('Git checkout'){
      steps {
          echo "Git clone the repo"
      }
    }
        stage('Build'){
      steps {
          echo "Build the App"
      }
    }
        stage('Unit Tests'){
      steps {
          echo "Test your App"
      }
    }
        stage('Deploy'){
      steps {
          echo "Deploy your App"
      }
    }
    }
}

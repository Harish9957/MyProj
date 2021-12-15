pipeline {
    agent any
    stages{
    stage('Git Checkout the Code'){
      steps {
          echo "Git clone the repo"
      }
    }
        stage('Build'){
            
      steps {
         printThis()
      }
    }
        stage('Unit Tests'){
      steps {
          echo "Testing your App"
      }
    }
        stage('Deploy'){
      steps {
          echo "Deploy your App in test env"
      }
    }
    }
}

def printThis()
{
     print('Its good')   
}

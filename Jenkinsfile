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
          echo "Test your App in DEV ENV"
      }
    }
        stage('Deploy'){
      steps {
          echo "Deploy your App in dev env"
      }
    }
    }
}

def printThis()
{
     print('Its good')   
}

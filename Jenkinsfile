pipeline {
agent any
  stages {
    stage ("checkout") {
      steps {
      git  " https://github.com/sk143405/game-of-life.git "
      }
    }
      stage ("build") {
       steps {
         mvn compile
       }
      }
    
    stage ("code analysis") {
      steps {
        mvn sonar:sonar \
           -Dsonar.projectKey=test \
           -Dsonar.login=ef0b0a0cf752f3555e69279070e99c9dc951becb
      }
    }
    
    stage ("artifact") {
      steps {
        script 
      def SERVER_ID:artifact.server
      }
    }
    }
  }
 



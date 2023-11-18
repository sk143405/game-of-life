pipeline {
agent any
  stages {
    stage ("checkout") {
      steps {
      git  " https://github.com/sk143405/game-of-life.git "
      }
      stage ("build") {
       steps {
         mvn compile
       }
      }
    }
  }
} 



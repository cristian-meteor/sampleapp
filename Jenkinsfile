pipeline {
  agent {
    docker {
      image 'maven:3.5-alpine'
    }
    
  }
  stages {
    stage('welcome') {
      steps {
        echo 'hola mundo jenkins'
      }
    }
    stage('unit test') {
      steps {
        sh 'mvn test'
      }
    }
  }
}
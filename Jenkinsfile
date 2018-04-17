pipeline {
  agent {
    docker {
      image 'maven:3.5.2-jdk-9'
    }
    
  }
  stages {
    stage('Say Hello') {
      agent {
        docker {
          image 'maven:3.5.2-jdk-9'
        }
        
      }
      steps {
        echo 'Hello'
        sh 'java -version'
      }
    }
  }
}
pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
    }
    
  }
  stages {
    stage('Stage1') {
      steps {
        echo 'We are in stage 1'
      }
    }
    stage('Jdk Validation') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_144'
  }
}
pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
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
        sh 'ls -l'
      }
    }
  }
}
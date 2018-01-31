pipeline {
  agent {
    docker {
      args 'F:\\.m2'
      image 'maven:3.3.9-jdk8 -v'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'echo "Building test project..."'
      }
    }
  }
}
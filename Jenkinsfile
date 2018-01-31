pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk8'
      args '-v "F:\\.m2"'
    }
    
  }
  stages {
    stage('initialize') {
      steps {
        sh '''echo "Initialize project..."










'''
      }
    }
    stage('Build') {
      steps {
        sh ' echo "Building the project.."'
      }
    }
  }
}
pipeline {
  agent {
    label 'docker' 
  }
  stages {
    stage('Docker maven test') {
      agent {
        docker {
          label 'docker'
          image 'maven:3-alpine'
        }
      }
      steps {
        sh 'mvn --version'
      }
    }
  }
} 

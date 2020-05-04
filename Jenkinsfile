pipeline {
  agent none
  stages {
    stage('Build Maven Project') {
      agent {
          docker { image 'maven:3-alpine' }
      }
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}

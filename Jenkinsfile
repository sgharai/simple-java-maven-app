pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
  stages {
    stage('Build Maven Project') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}

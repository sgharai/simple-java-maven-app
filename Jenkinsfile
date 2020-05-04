pipeline {
  agent { label 'master' }
  stages {
    stage('Build Maven Project') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('Testing') {
      steps {
        echo 'running tests'
        sh 'mvn test'
      }
    }
    stage('Build') {
      steps {
        echo 'Building jar files...'
        sh 'mvn package'
      }
    }
  }
}

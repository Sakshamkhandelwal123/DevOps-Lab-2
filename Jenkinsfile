pipeline {
  agent any
  stages {
    stage('Testing') {
      steps {
        echo 'running tests'
        bat 'mvn test'
      }
    }
    stage('Build') {
      steps {
        echo 'Building jar files...'
        bat 'mvn package'
      }
    }
  }
}

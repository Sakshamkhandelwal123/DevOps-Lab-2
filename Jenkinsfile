pipeline {
  agent any
  stages {
    stage('Testing') {
      steps {
        echo 'running tests'
        sh 'maven test'
      }
    }
    stage('Build') {
      steps {
        echo 'Building jar files...'
        sh 'maven package'
      }
    }
  }
}

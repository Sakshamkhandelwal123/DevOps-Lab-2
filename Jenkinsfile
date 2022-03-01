// pipeline {
//   agent any
//   stages {
//     stage('Testing') {
//       steps {
//         echo 'running tests'
//         sh 'mvn test'
//       }
//     }
//     stage('Build') {
//       steps {
//         echo 'Building jar files...'
//         sh 'mvn package'
//       }
//     }
//   }
// }
pipeline {
    agent any
    tools { 
        maven 'Maven 3.6.3'
        jdk 'jdk11' 
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}

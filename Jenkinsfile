pipeline {
    agent { 
        node {
            label 'hyperswitch'
            }
      }

    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
                cat cask
            }
        }
    }
}

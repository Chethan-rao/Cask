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
                cd ./Commands
                pwd
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                pwd
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                cat cask
                '''
                
            }
        }
    }
}

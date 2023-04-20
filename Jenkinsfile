pipeline {
    agent any

    stages {
        stage('Date') {
            steps {
                script {
                    sh 'echo "$(date)" >> /tmp/testpipeline'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

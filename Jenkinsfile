pipeline {
    agent any

    stages {
        stage('Date') {
            steps {
                echo 'Printing date to log file'
                script {
                    sh 'echo "$(date)" >> /tmp/testpipeline.log'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                script {
                    sh 'echo "Build completed"'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                script {
                    sh 'echo "Test completed"'
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                script {
                    sh 'echo "Deployment completed"'
                }
            }
        }
        stage('exit status') {
            steps {
                echo 'Finished!'
            }
        }            
    }
}

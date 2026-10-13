pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from version control...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo "Build step executed successfully."'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed successfully."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deployment completed."'
            }
        }
    }
}

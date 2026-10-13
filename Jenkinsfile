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
                bat "Build step executed successfully."
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat "Tests passed successfully."
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat "Deployment completed."
            }
        }
    }
}

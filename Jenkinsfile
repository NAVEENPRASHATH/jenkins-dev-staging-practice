pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out dev-staging code...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'type hello.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to Dev-Staging...'
            }
        }
    }
}

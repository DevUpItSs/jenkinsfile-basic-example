// Basic Jenkinsfile Example

pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning the repository...'
                // checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Example: sh 'make'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example: sh './deploy.sh'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from the GitHub repo
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production...'
                // Add your deployment commands here
            }
        }
    }
    post {
        success {
            echo 'Build was successful!'
        }
        failure {
            echo 'Build failed!'
        }
    }
}

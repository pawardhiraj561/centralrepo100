pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/spdevops95/new-demojob2.git'
            }
        }

        stage('Build') {
            steps {
                sh 'your-build-command-here'
            }
        }

        stage('Test') {
            steps {
                sh 'your-test-command-here'
            }
        }

        stage('Deploy') {
            steps {
                sh 'your-deployment-command-here'
            }
        }
    }
}

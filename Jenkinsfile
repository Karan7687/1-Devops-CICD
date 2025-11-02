pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
               git branch: 'master', url: 'https://github.com/Karan7687/1-Devops-CICD.git'

            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }
    }
}

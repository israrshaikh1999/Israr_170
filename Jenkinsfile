pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/user/repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Run your build commands here, e.g., sh 'npm install' or sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Run your test commands here, e.g., sh 'npm test' or sh 'pytest'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deploy scripts if needed
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Mag12code/tech1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add build commands here (e.g., npm install, mvn clean install)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., npm test, pytest)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment commands here
            }
        }
    }
}

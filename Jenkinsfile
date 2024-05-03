pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from GitHub repository
                git 'https://github.com/mubeen456/Github_jenkins.git'
            }
        }
        stage('Build') {
            steps {
                // Build code using Maven
                echo "Building..."
            }
        }
        stage('Test') {
            steps {
                // Run tests
                echo "Test..."
            }
        }
        stage('Deploy') {
            steps {
                // Deploy code (example: to AWS EC2)
                echo "Deploying..."
            }
        }
    }
    
    post {
        always {
            // Send email notification
            emailext(
                to: "mubeenmuhammad098@gmail.com",
                subject: "Build Status Email",
                body: "Build log attached!",
                attachLog: true
            )
        }
    }
}

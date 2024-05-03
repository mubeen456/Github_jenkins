pipeline{

     agent any
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
}
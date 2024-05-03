pipeline {
    agent any

    environment {
        DIRECTORY_PATH = "${WORKSPACE}"
        TESTING_ENVIRONMENT = "TestingEnvironment"
        PRODUCTION_ENVIRONMENT = "ASAD" // Your production environment name
    }
    
    stages {
        stage('Build') {
            steps {
                echo "Building..."
            }
            post{
                always{
                    mail to: "mubeenmuhammad098@gmail.com",
                    subject: "Build Status Email",
                    body: "Build log attached!"
                }
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}

pipeline{
    
     agent any

     environment {
        DIRECTORY_PATH = "${WORKSPACE}"
        TESTING_ENVIRONMENT = "TestingEnvironment"
        PRODUCTION_ENVIRONMENT = "ASAD" // Your production environment name
    }
    stage('Build') {
        steps {
            echo "Building..."
        }
    }
    stage('Test') {
        steps {
            echo "Testing..."
        }
    }
    stage('Deploy') {
        steps {
            echo "Deploy..."
        }
    }
}
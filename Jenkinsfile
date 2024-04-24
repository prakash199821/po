pipeline {
    agent any
    
    environment {
        // Define environment variables for the AWS access key and secret key
        credentialsId: 'AWS',
    }

    stages {
        stage('Example Stage') {
            steps {
                // Your pipeline steps here
                echo "AWS Access Key ID: ${AWS_ACCESS_KEY_ID}"
                echo "AWS Secret Access Key: ${AWS_SECRET_ACCESS_KEY}"
            }
        }
    }
}


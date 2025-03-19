pipeline {
    agent any

    environment {
        // You can define environment variables here
        MY_ENV_VAR = 'value'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build commands here (e.g., Maven, Gradle)
                sh 'echo "Building the project"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your testing commands here (e.g., unit tests)
                sh 'echo "Running tests"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment commands here (e.g., copy to server, deploy using tools)
                sh 'echo "Deploying application"'
            }
        }
    }

    post {
        always {
            echo 'Cleaning up...'
            // You can perform cleanup tasks here
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout stage'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests completed successfully'
            }
        }
    }

    post {
        success {
            echo 'CI pipeline completed successfully!'
        }
    }
}
// webhook test
// Webhook test update Tue Oct 13 15:04:34 UTC 2026

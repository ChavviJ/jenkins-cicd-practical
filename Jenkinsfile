
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage executed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }

    post {
        success {
            echo 'CI/CD pipeline completed successfully'
        }
    }
}

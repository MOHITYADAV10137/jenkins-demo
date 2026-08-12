pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build Started"'
                sh 'echo "Build Completed"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing Started"'
                sh 'echo "Testing Completed"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deployment Started"'
                sh 'echo "Deployment Completed"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline Successfully Completed'
        }

        failure {
            echo 'Pipeline Failed'
        }
    }
}

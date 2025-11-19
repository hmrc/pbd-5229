pipeline {
    stages {
        stage('Checkout') {
            steps {
                echo "Checking out source code..."
                sh 'echo "Pretending to check out source code"'
            }
        }
        stage('Build') {
            steps {
                echo "Building Fun Service..."
                sh 'echo "Pretending build process"'
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo "Simulating tests"'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo "Simulating deployment"'
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
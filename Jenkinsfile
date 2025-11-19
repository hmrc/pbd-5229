pipeline {
    agent {
        label 'bndcli-agent'
    }
    stages {
        stage('Checkout') {
            steps {
                echo "Checking out source code..."
                script {
                    sh 'echo "Pretending to check out source code"'
                }
            }
        }
        stage('Build') {
            steps {
                echo "Building Fun Service..."
                script {
                    sh 'echo "Pretending build process"'
                }
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                script {
                    sh 'echo "Simulating tests"'
                }
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying application..."
                script {
                    sh 'echo "Simulating deployment"'
                }
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
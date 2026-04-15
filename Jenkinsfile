pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Checking out code..."
                git 'https://github.com/Karthi1509/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
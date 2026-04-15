pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Cloning repository..."
                git 'https://github.com/YOUR_USERNAME/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage (Python doesn't need compilation)"
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                echo "Running Python script..."
                sh 'python3 app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy stage"
                sh 'echo Deployment simulated'
            }
        }
    }
}
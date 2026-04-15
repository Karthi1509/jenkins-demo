pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Cloning repository..."
                git 'https://github.com/Karthi1509/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Checking Python version..."
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                echo "Running Python app..."
                sh 'python3 app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                sh 'echo Deployment completed'
            }
        }
    }
}

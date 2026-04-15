pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deployment completed'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Starting Checkout Stage'
                sh 'pwd'
                sh 'ls'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Docker Image'
                sh 'docker build -t nexatech-website:latest ./app'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Docker Image'
                sh 'docker image inspect nexatech-website:latest'
            }
        }
    }
}

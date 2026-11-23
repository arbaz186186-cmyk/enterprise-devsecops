pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out project code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building NexaTech website Docker image'
                sh 'docker build -t nexatech-website:latest ./app'
            }
        }

        stage('Test') {
            steps {
                echo 'Checking Docker image'
                sh 'docker image inspect nexatech-website:latest'
            }
        }
    }
}

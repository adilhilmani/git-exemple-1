pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build OK"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Tests OK"'
            }
        }
    }
}

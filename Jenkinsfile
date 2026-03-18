pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                sh 'git checkout c0c9c6ee47d2aa8336dc67527744a482af4ef40e'
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

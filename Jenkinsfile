pipeline {
    agent any
    environment {
        CI = 'true'
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo "multibranch Pipleine test-2"'
            }
        }

        stage('Test') {
            steps {
                sh 'ls'
            }
        }
    }
}



pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Example test commands
                // sh 'make test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                bat 'java HelloWorld'
            }
        }
    }
}

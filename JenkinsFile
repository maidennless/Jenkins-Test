pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'javac HelloWorld.java
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
                sh 'java HelloWorld'
            }
        }
    }
}

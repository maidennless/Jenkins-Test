pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                javac HelloWorld.java
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
                java HelloWorld
            }
        }
    }
}

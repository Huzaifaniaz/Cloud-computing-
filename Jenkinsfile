pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Checkout code from your repository
                checkout scm
                
                // Replace with your build commands
                sh 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                // Replace with your test commands
                sh 'java YourTestFile'
            }
        }

        stage('Deploy') {
            steps {
                // Replace with your deployment commands
                sh 'java HelloWorld'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                checkout scm
                
                sh 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java YourTestFile'
            }
        }

        stage('Deploy') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}

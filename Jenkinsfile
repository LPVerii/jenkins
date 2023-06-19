pipeline {
    agent any

    stages {
        stage('Install Python') {
            steps {
                script {
                    // Install Python using shell commands
                    sh 'apt-get update'
                    sh 'apt-get install -y python3'
                }
            }
        }
        
        stage('Build and Test') {
            steps {
                // Run Python commands or scripts here
                sh 'python3 --version'
                sh 'pip3 --version'
                // Execute your build and test steps
            }
        }
    }
}

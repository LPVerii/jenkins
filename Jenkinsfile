pipeline {
    agent any

    tools {
        // Specify the Python installation
        nodejs 'python' // Assuming you have configured Python as a NodeJS tool installation in Jenkins
    }

    stages {
        stage('Build and Test') {
            steps {
                // Run Python commands or scripts here
                sh 'python --version'
                sh 'pip --version'
                // Execute your build and test steps
            }
        }
    }
}

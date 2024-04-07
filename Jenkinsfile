pipeline {
    agent any
    
    options {
        skipDefaultCheckout() // Skip the default checkout to allow custom checkout per stage
    }
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'your-build-command'
            }
        }
        // Add more stages as needed
    }
}

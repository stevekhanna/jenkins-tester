 pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the GitHub repository
                git 'https://github.com/stevekhanna/jenkins-tester.git'
            }
        }
        
        stage('Run Python Script') {
            steps {
                // Execute the Python script
                sh 'python src/main.py'
            }
        }
    }
 }
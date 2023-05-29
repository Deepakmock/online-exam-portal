pipeline {
    agent any
  
  tools {nodejs "hagen"}
 
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout your Node.js project from the repository
                git 'git@github.com:Deepakmock/online-exam-portal.git'
            }
        }
        
        stage('Install Dependencies') {
            steps {
                // Install Node.js dependencies
                sh 'npm i'
            }
        }
        
        stage('Build and Package') {
            steps {
                // Build and package your Node.js project
              
              sh 'npm run start'
            }
        }
        }
        }

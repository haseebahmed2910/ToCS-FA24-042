pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                // Clone or pull the latest code from the repository
                git branch: 'main', // Replace 'main' with your branch name
                    credentialsId: 'your-credentials-id', // Jenkins credentials ID
                    url: 'git@github.com:aalishan808/ToCS-FA24-045.git'
            }
        }
        stage('Build and Sync') {
            steps {
                script {
                    // Sync logic here
                    sh 'echo "Syncing changes..."'
                }
            }
        }
    }
}

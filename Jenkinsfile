pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                git 'https://github.com/Mariam22-hub/cloud-pipeline.git'
            }
        }

        stage('Execute Batch File') {
            steps {
                // Run the batch file
                bat 'cloud.bat'
            }
        }
    }
}

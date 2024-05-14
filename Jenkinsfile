pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                git 'https://github.com/your-repo-url.git'
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

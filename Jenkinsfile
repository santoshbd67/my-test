pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    git credentialsId: 'github_id', url: 'https://github.com/santoshbd67/my-test.git'
                }
            }
        }

        // Additional stages...
    }

    post {
        always {
            // Cleanup or additional actions can go here
        }
    }
}

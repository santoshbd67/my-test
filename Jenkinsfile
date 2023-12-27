pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    // Use the credentials ID you created in Jenkins
                    git credentialsId: 'githu_id', url: 'https://github.com/santoshbd67/my-test.git'
                }
            }
        }

        // Additional stages and steps...
    }

    post {
        always {
            // Cleanup or additional actions can go here
        }
    }
}

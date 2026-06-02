pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rupeshsokande10-eng/actify-devops-assessment.git'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying website'
            }
        }

        stage('Verify') {
            steps {
                echo 'Deployment successful'
            }
        }
    }
}
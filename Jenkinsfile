pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
post {
        success {
            echo 'Success...'
            echo 'Send status Success to Mail, Telegram, Slack...'
        }
        failure {
            echo 'Failure...'
            echo 'Send status Failure to Mail, Telegram, Slack...'
        }
    }
}

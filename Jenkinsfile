pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests2...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
    post {
        cleanup {
            deleteDir()
        }
    }
}

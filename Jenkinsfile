pipeline {
    agent any

    stages {
        stage('Main') {
            when {
                branch 'main'
            }
            steps {
                echo 'In main'
            }
        }
        stage('Dev') {
            when {
                branch 'dev'
            }
            steps {
                echo 'In dev'
            }
        }
    }
    post {
        cleanup {
            deleteDir()
        }
    }
}

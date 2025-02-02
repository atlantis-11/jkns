pipeline {
    agent any

    stages {
        stage('Main') {
            when {
                branch 'origin/main'
            }
            steps {
                echo 'In main'
            }
        }
        stage('Dev') {
            when {
                branch 'origin/dev'
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

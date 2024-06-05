pipeline {
    agent any
    stages {
        stage('Control Docker Compose Services') {
            steps {
                bat 'start /B docker-compose up -d'
            }
        }
    }
}

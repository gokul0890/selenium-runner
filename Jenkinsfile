pipeline {
    agent none
    stages {
        stage('docker up') {
            steps {
                bat 'docker-compose up'
            }
        }
        stage('docker down') {
            steps {
		bat 'docker-compose down'
            }
        }
    }
}
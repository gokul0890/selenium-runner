pipeline {
    agent any
    stages {
        stage('docker up') {
            steps {
                docker-compose up
            }
        }
        stage('docker down') {
            steps {
		docker-compose down
            }
        }
    }
}
pipeline {
    agent none
    stages {
        stage('docker up') {
            steps {
                sh 'docker-compose up'
            }
        }
        stage('docker down') {
            steps {
		sh 'docker-compose down'
            }
        }
    }
}
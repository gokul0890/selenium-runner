pipeline {
    agent any
    stages {
        stage('docker up') {
            steps {
		script{
			docker-compose up
		}
                
            }
        }
        stage('docker down') {
            steps {
		script{
			docker-compose down
		}
            }
        }
    }
}
pipeline {
agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                sh 'sudo docker build -t test:1 .'
            }
        }
        stage('Test') {
            steps {
                sh 'sudo docker-compose up config'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sudo docker-compose up -d'
            }
        }
    }
}


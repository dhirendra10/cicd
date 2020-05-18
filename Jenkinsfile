pipeline {
agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t test:1 .'
            }
        }
        stage('Test') {
            steps {
                echo 'checking'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


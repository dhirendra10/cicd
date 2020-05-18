pipeline {
agent { label 'master' }
    stages {
        stage('Build') {
            steps {
                echo 'docker build -t test:1 .'
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


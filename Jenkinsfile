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
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}


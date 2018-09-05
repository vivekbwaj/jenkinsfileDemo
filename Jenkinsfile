pipeline {
    agent {
        docker { image 'node:8-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'node --version'
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
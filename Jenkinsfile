pipeline {
    agent {
        docker { image 'node:17-alpine3.14' }
    }
    stages {
        stage('Installation') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm run test'
            }
        }
        stage('Prettier') {
            steps {
                sh 'npm run prettier'
            }
        }
        stage('Linting') {
            steps {
                sh 'npm run lint'
            }
        }
    }
}
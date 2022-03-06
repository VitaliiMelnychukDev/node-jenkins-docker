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
    }
}
pipeline {
    agent {
        docker { image 'node:17-alpine3.14' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
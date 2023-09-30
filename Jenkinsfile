pipeline {
    agent {
        docker { image 'node:18.16.0-alpine' }}
    stages {
        stage('Testing') {
            steps {
                sh 'node --version'
            }
        }
    }
}

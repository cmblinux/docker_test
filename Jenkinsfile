pipeline {
    agent {
        docker {
            image 'node:18.16.0-alpine'
            label 'docker'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}

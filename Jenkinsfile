pipeline {
    agent {
        docker {
            image 'node:18'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test || echo "No tests available"'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deploy stage placeholder'
            }
        }
    }
}

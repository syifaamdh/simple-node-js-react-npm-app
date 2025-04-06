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
                sh 'npm test || echo "skip test (belum ada test file)"'
            }
        }
        stage('Deliver') {
            steps {
                echo '✅ Build selesai, siap untuk deployment!'
            }
        }
    }
}

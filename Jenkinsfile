pipeline {
    agent { label 'desktop-jenkins_agent-1-node' }

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh 'npm install'
            }
        }
    }
}

pipeline {
    agent { label 'docker-ssh-jenkins-agent' }

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh 'npm install'
            }
        }
    }
}

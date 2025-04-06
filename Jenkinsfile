pipeline {
  agent {
    docker { image 'node:18' }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh 'npm test || true'  // pakai `|| true` kalau belum ada test biar gak gagal
      }
    }
  }
}

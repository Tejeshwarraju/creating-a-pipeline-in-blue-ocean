pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6-alpine'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh '''sudo -s
npm install'''
      }
    }
  }
}
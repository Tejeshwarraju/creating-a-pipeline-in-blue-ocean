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
        sh 'sudo npm install --unsafe-perm=true --allow-root'
      }
    }
  }
}
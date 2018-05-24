pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'npm install'
      }
    }
  }
}
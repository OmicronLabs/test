pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'npm install'
      }
    }
  }
}
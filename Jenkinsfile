pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}
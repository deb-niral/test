pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'Startting build stage'
        sh 'node --version'
      }
    }

  }
}
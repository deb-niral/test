pipeline {
  agent {
    docker {
      image 'golang'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'Startting build stage'
        sh 'go version'
      }
    }

  }
}
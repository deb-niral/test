pipeline {
  agent {
    docker {
      image 'ubuntu:18.04'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'Startting build stage'
        sh 'make'
      }
    }

  }
}
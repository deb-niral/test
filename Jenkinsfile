pipeline {
  agent {
    docker {
      image 'golang'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'Startting build stage now'
        sh 'go build hello.go'
      }
    }

    stage('run') {
      steps {
        sh './hello'
      }
    }

  }
}
pipeline {
  agent {
            docker {
            image 'golang:latest' // The Docker image containing Go environment
        }
  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}

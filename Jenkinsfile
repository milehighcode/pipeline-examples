pipeline {
  agent {
    docker {
      image 'alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        cleanWs(cleanWhenSuccess: true)
      }
    }
  }
  environment {
    stage = 'all'
  }
}
pipeline {
  agent {
    docker {
      image 'node:7.10'
      args '-v $(pwd):/app -w /app node:7.10 node helloworld.js'
    }

  }
  stages {
    stage('Test') {
      steps {
        echo 'test'
      }
    }
  }
}
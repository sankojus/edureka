pipeline {
  agent {
    docker {
      image 'busybox'
      args 'cat'
    }

  }
  stages {
    stage('step1') {
      steps {
        sh 'echo "first step1"'
      }
    }

    stage('stage2') {
      steps {
        sh '''echo "hello"
'''
      }
    }

  }
}
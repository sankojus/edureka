pipeline {
  agent { docker 'busybox:latest' }
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

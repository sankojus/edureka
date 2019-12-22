def user = "$user"
pipeline {
  agent { label docker }
  stages {
    stage('step1') {
      steps {
        sh 'echo "this is my first step $user "'
      }
    }

    stage('stage2') {
      steps {
        sh '''echo "hello $user"
'''
      }
    }

  }
}

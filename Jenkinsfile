pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh ''' 
        pwd
        ls -lrth
        cd $workspace/src
        docker build -t takacsmark/alpine-smarter:1.0 
        '''
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

pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh ''' 
        pwd
        ls -lrth
        
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

pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh ''' 
        pwd
        ls -lrth
        cd $workspace/
        cd /home/ec2-user/jenkins_home/workspace/pipeline1/src
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

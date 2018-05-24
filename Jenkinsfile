pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        dockerfile {
          filename 'docker/px4-dev/Dockerfile_base'
        }

      }
      steps {
        sh 'uname -a'
      }
    }
  }
}
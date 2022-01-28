pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building image'
        sh 'docker.build registry'
      }
    }

  }
  environment {
    Registry = '431522056424.dkr.ecr.us-east-2.amazonaws.com/my-docker-repo'
  }
}
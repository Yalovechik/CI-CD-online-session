pipeline {
  agent any
  stages {
    stage('Check-out') {
      steps {
        git(url: 'https://github.com/Yalovechik/cicd-pipeline.git', branch: 'main')
      }
    }

  }
  environment {
    registry = 'yalovechik/test'
  }
}
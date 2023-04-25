pipeline {
  agent any
  stages {
    stage('Check-out') {
      steps {
        git(url: 'https://github.com/Yalovechik/cicd-pipeline.git', branch: 'main')
      }
    }

    stage('error') {
      steps {
        sh '''#!/bin/bash
npm run build'''
      }
    }

  }
  environment {
    registry = 'yalovechik/test'
  }
}
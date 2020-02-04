pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''npm cache clean --force
npm-upgrade core-js
npm install'''
      }
    }

  }
}
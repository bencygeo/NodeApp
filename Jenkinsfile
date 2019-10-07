pipeline {
  agent { /usr/local/bin/docker 'node:6.3' }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
        sh 'npm install'
        sh 'npm test'
      }
    }
  }
}

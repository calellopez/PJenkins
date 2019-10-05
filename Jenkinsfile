pipeline {
  agent any
  stages {
    stage('build assets') {
      steps {
        dir(path: 'sell script') {
          sh 'npm install'
          sh 'npm run scss:prod'
          sh 'npm run sript:prod'
        }

      }
    }
  }
}
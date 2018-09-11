pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('Run') {
      steps {
        sh 'npm start'
      }
    }
  }
}
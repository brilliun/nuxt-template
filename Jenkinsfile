pipeline {
    agent any
    stages {
        stage('Preparation') { // for display purposes
          steps {
            sh 'npm install'
          }
        }
        stage('Build') {
          steps {
            sh 'npm run build'
          }
        }
        stage('Results') {
          steps {
            echo 'Succeed'
          }
        }
    }
}
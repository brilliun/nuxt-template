pipeline {
    agent node
    stages {
        stage('Preparation') { // for display purposes
            sh 'npm install'
        }
        stage('Build') {
            sh 'npm run build'
        }
        stage('Results') {
            echo 'Succeed'
        }
    }
}
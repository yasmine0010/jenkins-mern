pipeline {
    agent any
    tools { nodejs "NodeJS" }
    stages {
        stage('Build') { 
            steps {
                sh 'rm -rf *'
                sh 'npm install' 
            }
        }
    }
}
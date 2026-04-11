pipeline {
    agent any
    stages {
        stage('Docker Check 1st time') {
            steps {
                sh 'docker --version'
                sh 'docker ps'
            }
        }
         stage('Docker Check 2nd') {
            steps {
                sh 'docker --version'
                sh 'docker ps'
            }
        }
    }
}

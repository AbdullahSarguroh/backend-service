pipeline {
    agent any
    stages {
        stage('Docker Check 1') {
            steps {
                sh 'python --version'
                
            }
        }
        stage('Docker Check 2 another stage') {
            steps {
                sh 'npm --version'
                sh 'node --version'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Pull Code') {
            steps {
                git 'https://github.com/sushanthreddy009/jenkins-test-node.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to server...'
            }
        }
    }
}

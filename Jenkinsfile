pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                bat 'echo Pulling Code'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Application'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying...'
            }
        }
    }
}

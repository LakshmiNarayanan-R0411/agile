pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/LakshmiNarayanan-R0411/agile.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'echo Build step executed'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Test step executed'
            }
        }
    }
}

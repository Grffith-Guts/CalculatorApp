pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning the repository...'
                git url: 'git@github.com:Grffith-Guts/CalculatorApp.git', credentialsId: 'GITSHH'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}


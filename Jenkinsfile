pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Step'
                sleep 10
            }
        }
        stage('Test') {
            steps {
                echo 'Test step'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Step'
                sleep 10
            }
        }
        stage('Docker') {
            steps {
                echo 'Image step'
            }
        }
    }

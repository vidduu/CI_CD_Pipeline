pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/vidduu/CI_CD_Pipeline.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy commands here
            }
        }
    }
}


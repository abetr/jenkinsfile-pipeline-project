pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Amını dizine"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('Jenkinsfile') {
            steps {
                echo 'Ardını dövdürme'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
    }
}
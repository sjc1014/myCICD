pipeline {
    agent any 
    stages {
        stage('Stage SCM Polling') {
            steps {
                echo 'SCM GitHub says Hello World!!' 
            }
        }
        stage('Checking Docker Version') {
            steps {
                sh 'docker --version'
            }
        }
    }
}

@Library('pipeline-library-demo')_

pipeline {
    agent { label 'slave' }
    stages {
        stage('Hello') {
            steps {
                sh 'java -version'
                echo 'Get working directory'
                sh 'pwd'
            }
        }
        stage('Hello-Library') {
            steps {
                echo 'Hello World!'
                sayHello('Steve')
            }
        }
    }
}

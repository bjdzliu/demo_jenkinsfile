pipeline {
    agent any 
            stage('Checkout Source') {
            steps {
                ws("${workspace}") {
                    checkout scm
                }
            }
        }
    stages {
        stage('print') {
            steps {
                echo 'Hello world!' 
            }
        }
    }
}

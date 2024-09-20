pipeline {
    agent any 
    stages {
                    stage('Checkout Source') {
            steps {
                ws("${workspace}") {
                    checkout scm
                }
            }
        }
        stage('print') {
            steps {
                echo 'Hello world!' 
            }
        }
    }
}

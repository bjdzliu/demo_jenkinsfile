pipeline {
    agent any 
    stages {
                stage('ls') {
            steps {
                sh "ls -l"
            }
        }
        
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

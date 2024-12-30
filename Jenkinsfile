pipeline {
    agent any 
    triggers {
        githubPush() // 监听GitHub Push事件
    }
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

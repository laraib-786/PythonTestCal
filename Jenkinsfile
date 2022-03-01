pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    triggers {
        cron('0 0 * * *')
    }
    stages {
        stage('Compile') {
            steps {
                echo 'hello world' 
            }
        }
        stage('Unit Test'){
            steps{
                sh 'python test.py'
            }
        }
    }
}

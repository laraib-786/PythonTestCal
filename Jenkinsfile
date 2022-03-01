pipeline {
    agent any
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

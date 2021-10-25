pipeline {
    agent any 
    stages {
        stage('Compile') {
            steps {
                echo 'hello world' 
            }
        }
        stage('Unit Test'){
            steps{
                sh 'test.py'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Stage-1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Stage-2') {
            steps {
                echo 'Hello World'
            }
        }        
        stage('Docker') {
            steps {
                sh 'docker build -t praveen .'
            }
        }        
    }
}

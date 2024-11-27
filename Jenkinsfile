pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'ant compile'
            }
        }
        stage('Test') {
            steps {
                sh 'ant test'
            }
        }
        stage('Package') {
            steps {
                sh 'ant package'
            }
        }
        stage('Deploy') {
            steps {
                sh 'ant deploy'
            }
        }
    }
}
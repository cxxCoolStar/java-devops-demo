pipeline {
    agent any
    stages {
        stage('Check') {
            steps {
                sh 'printenv'
                sh 'java -version'
                sh 'git --version'
                sh 'docker version'
                //sh 'mvn -v'
                sh '666'
            }
        }
        stage('Build') {
            steps {
                //
                echo "building"
            }
        }
        stage('Test') {
            steps {
                //
               echo "testing"
               //emailext body: 'test', subject: '', to: '184505943@qq.com'
            }
        }
        stage('Deploy') {
            steps {
                //
               echo "deploying"
            }
        }
    }
}
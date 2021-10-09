pipeline {
    agent any
    stages {
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
               emailext body: 'test', subject: '', to: '184505943@qq.com'
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
pipeline {
    agent any

    stages {
        stage('list home directory contents') {
            steps {
                sh 'cd /home/ubuntu/;ls'
            }
        }
        stage('hello') {
            steps {
                echo 'hello'
            }
        }
        stage('hello1') {
            steps {
                sh 'cd /home/ubuntu/; cat hardik'
            }
        }
    }
}

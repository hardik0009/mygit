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
    }
}

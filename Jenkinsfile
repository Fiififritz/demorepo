pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Run web page') {
            steps {
                sh 'cat index.html'
            }
        }
        stage('Run multi command') {
            steps {
                sh '''
                whoami
                cal
                dir
                '''
            }
        }
    }
}

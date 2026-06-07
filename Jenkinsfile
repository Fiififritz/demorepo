pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Run Linux command') {
            steps {
                sh 'date'
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

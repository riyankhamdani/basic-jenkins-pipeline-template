pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building application...'
                // Jalankan perintah build standar di sini
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Jalankan unit test di sini
            }
        }
    }
}


pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Jenkins da lay source code.'
            }
        }

        stage('Check project files') {
            steps {
                bat 'dir'
                bat 'if exist index.html (echo Da tim thay index.html) else (echo Khong tim thay index.html & exit /b 1)'
            }
        }

        stage('Build completed') {
            steps {
                echo 'Pipeline hoan thanh!'
            }
        }
    }
}

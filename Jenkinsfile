pipeline {
    agent any

    stages {
        stage('Development Environment') {
            steps {
                echo 'Hello World Development'
                bat 'mkdir C:\\ProgramData\\Jenkins\\newFile'
            }
        }
        stage('QA') {
            steps {
                echo 'Hello World QA'
            }
        }
        stage('Unit') {
            steps {
                echo 'Hello World Unit'
            }
        }
        stage('Pre production') {
            steps {
                echo 'Hello World Pre production'
            }
        }
    }
}


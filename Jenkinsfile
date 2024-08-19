pipeline {
    agent any

    stages {
        stage('Development Environment') {
            steps {
                echo 'Hello World Development'
                bat 'git clone https://github.com/Pavith-web/Demo3.git'
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


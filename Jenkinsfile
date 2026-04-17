pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Compiling Java program...'
                bat 'javac BankService.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java program...'
                bat 'java BankService'
            }
        }

    }
}

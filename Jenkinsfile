pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java program...'
                bat 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java program...'
                bat 'java Main'
            }
        }
    }
}

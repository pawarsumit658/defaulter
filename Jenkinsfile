pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/pawarsumit658/defaulter.git'
            }
        }

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

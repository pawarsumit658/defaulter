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
                sh 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running Java program...'
                sh 'java Main'
            }
        }
    }
}

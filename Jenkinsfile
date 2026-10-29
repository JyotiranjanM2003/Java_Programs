
pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Starting Java compilation...'
                bat 'javac Helloworld.java'
                echo 'Java compilation completed successfully!'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Java program...'
                bat 'java Helloworld'
                echo 'Java program executed successfully!'
            }
        }
    }
}

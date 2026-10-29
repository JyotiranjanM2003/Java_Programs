
pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Starting Java compilation...'
                bat 'javac HelloWorld.java'
                echo 'Java compilation completed successfully!'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Java program...'
                bat 'java HelloWorld'
                echo 'Java program executed successfully!'
            }
        }
    }
}

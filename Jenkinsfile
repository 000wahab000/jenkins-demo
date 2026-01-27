pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'C:\\Users\\family\\Maven\\apache-maven-3.9.12\\bin\\mvn.cmd clean compile'
            }
        }

        stage('Test') {
            steps {
                bat 'C:\\Users\\family\\Maven\\apache-maven-3.9.12\\bin\\mvn.cmd test'
            }
        }

    }
}

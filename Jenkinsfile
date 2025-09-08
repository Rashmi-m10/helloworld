pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git ""
            }
        }
        stage('Compile') {
            steps {
                bat 'javac hello.jav'
            }
        stage('Run') {
            steps {
               bat 'java hello'
            }
        }
    }
}

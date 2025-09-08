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
                bat 'javac HelloWorld.java'
            }
        stage('Run') {
            steps {
               bat 'java HelloWorld'
            }
        }
    }
}

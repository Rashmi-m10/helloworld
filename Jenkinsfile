pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git 'https://github.com/Rashmi-m10/helloworld.git'
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

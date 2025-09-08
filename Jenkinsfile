pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', credentialsId: 'c6c3d005-a905-408d-a31e-5de9e7e4a0c5', url: 'https://github.com/Rashmi-m10/helloworld.git'
            }
        }
        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
               bat 'java HelloWorld'
            }
        }
    }
}

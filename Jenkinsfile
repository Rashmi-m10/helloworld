pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git url:'https://github.com/Rashmi-m10/helloworld.git', branch: 'main'
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

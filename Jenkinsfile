pipeline {
    agent any
    tools{
        jdk 'jdk1.8'
    }
    stages {
        stage('Build') {
            steps {
               echo 'Building..' 
                bat "javac Hello.java"
                bat "java Hello"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
               
            }
        }
    }
}

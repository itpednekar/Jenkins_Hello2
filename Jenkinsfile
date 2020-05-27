pipeline {
    agent any
    tools{
        jdk 'jdk1.8'
    }
    stages {
        stage('Build') {
            steps {
               echo 'Building..' 
                sh "javac Hello.java"
                sh "java Hello"
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

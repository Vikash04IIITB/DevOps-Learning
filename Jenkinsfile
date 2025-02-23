pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Vikash04IIITB/DevOps-Learning.git'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}

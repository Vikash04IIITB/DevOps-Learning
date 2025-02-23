pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Vikash04IIITB/DevOps-Learning.git'
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}

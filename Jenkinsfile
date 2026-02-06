pipeline{
    agent any
    stages{
        stage('Build Image'){
            steps{
                bat 'docker build -t demo-app .'
            }
        }
        stage('Run Container'){
            steps{
                bat 'docker run demo-app'
            }
        }
    }
}
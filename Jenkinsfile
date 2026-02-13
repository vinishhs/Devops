pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'dev',
                    url: 'https://github.com/vinishhs/Devops.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-app .'
            }
        }

        stage('Run Container') {
            steps {
                sh '''
                docker stop devops-container || true
                docker rm devops-container || true
                docker run -d -p 3001:3000 --name devops-container devops-app
                '''
            }
        }
    }
}

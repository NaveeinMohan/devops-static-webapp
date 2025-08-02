pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    docker.build('static-webapp-image', 'Static-WebApp')
                }
            }
        }

        stage('Run Container') {
            steps {
                script {
                    docker.image('static-webapp-image').run('-p 8080:80')
                }
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Arunsaxena899255/todo-app.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t todo-app .'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker rm -f todo || true'
                sh 'docker run -d -p 5000:5000 --name todo todo-app'
            }
        }
    }
}

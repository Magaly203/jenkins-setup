pipeline {
    agent any
    stages {
        stage('Setup') {
            steps {https://github.com/Magaly203/jenkins-setup.git' // Cambia esto por tu repositorio
            }
        }
        stage('Deploy') {
            steps {
                sh 'docker-compose down || true'
                sh 'docker-compose up -d'
            }
        }
    }
}

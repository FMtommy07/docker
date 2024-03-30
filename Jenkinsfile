pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Paso para clonar el repositorio
                git 'https://github.com/tu_usuario/mi-proyecto-nodejs.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                // Instalar las dependencias usando npm
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                // Ejecutar pruebas
                sh 'npm test'
            }
        }
    }
}

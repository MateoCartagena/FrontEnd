pipeline {
    agent any  // Usar cualquier agente disponible de Jenkins
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project!'
                // Aquí puedes poner comandos de compilación específicos para tu proyecto
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests!'
                // Aquí van los comandos para correr pruebas, como npm test o pytest
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application!'
                // Aquí puedes agregar pasos para desplegar el proyecto
            }
        }
    }
}

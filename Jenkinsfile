pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Test webhook') {
            steps {
                echo '¡Webhook recibido2! Construyendo rama develop.'
            }
        }
    }
}
pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Test webhook') {
            steps {
                echo '¡Webhook recibido! Construyendo rama develop.'
            }
        }
    }
}
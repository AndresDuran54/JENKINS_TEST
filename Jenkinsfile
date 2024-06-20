pipeline {
    agent {
        docker {
            image 'docker:20.10.7' // La imagen de Docker a utilizar
            args '-v /var/run/docker.sock:/var/run/docker.sock' // Monta el socket Docker del host
        }
    }
    stages {
        stage('Build') {
            steps {
                script {
                    echo "DEPLOY EJECUTANDOSE"
                    // sh "./deploy.sh"
                }
            }
        }
    }
}

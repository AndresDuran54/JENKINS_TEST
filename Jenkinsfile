pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh 'hola'
            }
        }
    }
    post { 
        failure { 
            echo 'Esta ejecución ha fallado'
        }
    }
}
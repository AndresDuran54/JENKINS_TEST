pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh 'echo "hola"'
            }
        }
    }
    post { 
        failure { 
            echo 'Esta ejecución ha fallado'
        }
    }
}
pipeline {
    agent {
        docker { image 'tomcat:8' }
    }
    stages {
        stage('Prod') {
            steps {
                sh 'echo Image pulled..'
            }
        }
    }
}

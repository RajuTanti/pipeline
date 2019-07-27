pipeline {
    agent {
        docker { image 'tomcat:8' }
    }
    stages {
        stage('Prod') {
            steps {
                sh 'docker run -d -p 8081:8080 --name tomcat8 tomcat:8'
            }
        }
    }
}

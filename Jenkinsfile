pipeline { 
    agent any
    stages {
        stage("verify tooling"){
            steps {
                sh '''

                docker info
                docker version
                docker compose version 
                java --version
                docker-compose down
                docker-compose build
                sh start.sh
                '''
            }
        }
    }
}

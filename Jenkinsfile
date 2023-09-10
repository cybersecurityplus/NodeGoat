pipeline { 
    agent any
    stages {
        stages("verify tooling"){
            steps {
                sh '''

                docker info
                docker version
                docker compose version 
                java --version
                '''
            }
        }
    }
}
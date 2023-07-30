pipeline {
    agent {
        docker { image 'node:16-alpine' }
    }

    stages {
        stage('Check Node and Version') {
            steps {
                sh 'node --version'
            }
        }
    }
}

pipeline {
    agent {
        docker {
            image 'node:14-alpine'
            label 'docker'
            alwaysPull true
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}

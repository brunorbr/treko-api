pipeline {
    agent {
        docker {
            image "node:8-alpine"
        }
    }
    stages {
        stage("build") {
            steps{
                sh "npm install"
            }
        }
    }
}
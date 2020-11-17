pipeline {
    agent {
        docker {
            image "node:8-alpine"
        }
    }
    stages {
        stage("build") {
            sh "npm install"
        }
    }
}
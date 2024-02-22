pipeline {
    agent {
        docker { image "node:hydrogen-bookworm"}
    }

    stages {
        stage('npm install') {
            steps {
                sh "npm install"
            }
        }

        stage('Build') {
            steps {
                sh ""
            }
        }

        stage('Run e2e tests') {
            steps {
                sh ""
            }
        }

        stage('Deploy') {
            steps {
                sh ""
            }
        }
    }
}
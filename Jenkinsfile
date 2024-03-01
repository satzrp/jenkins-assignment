pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                checkout scm
            }
        }
        stage('Copy Files') {
            steps {
                sh "echo copying files"
            }
        }
    }
}

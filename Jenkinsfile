pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself_new'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "My pipline job with jenkinsfile"
                sh 'echo jenkins-github-webhook job'
                sh 'python --version'
                sh 'python pipeline.py'
                
            }
        }
    }
}

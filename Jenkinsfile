pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "My pipline job with jenkinsfile"
                sh 'echo jenkins Poll SCM job'
                sh 'python --version'
                sh 'python pipeline.py'
                
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Compiling the java source code"
                sh 'java hello.java'
           }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java hello'
            }
        }
                
    }
}
    


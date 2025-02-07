pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        stage('Test') {
            steps {
                "jenkins\scripts\test.bat"
            }
        }
    }
}

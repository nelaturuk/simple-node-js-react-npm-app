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
                cd jenkins
                cd scripts
                bat "test.bat"
            }
        }
    }
}

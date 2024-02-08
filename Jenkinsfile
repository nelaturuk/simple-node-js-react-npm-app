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
                echo 'Hi I am testing'
            }
        }
    }
}

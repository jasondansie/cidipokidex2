pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                npm install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing from branch "develop"..'
            }
        }
        stage('Deploy') {
            steps {
                npm run Build
            }
        }
    }
}


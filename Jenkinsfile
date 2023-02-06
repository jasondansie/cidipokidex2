pipeline {
    agent any
    tools {nodejs "node"}

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing from branch "develop"..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'npm run build'
            }
        }
    }
}


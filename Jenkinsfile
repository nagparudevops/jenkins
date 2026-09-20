pipeline {
    

    stages {
        stage('Test Agent') {
            steps {
                sh 'whoami'
                sh 'hostname'
                sh 'pwd'
                sh 'java -version'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
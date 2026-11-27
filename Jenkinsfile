pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building DEV branch'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing DEV application'
            }
        }
        stage('Deployment') {
            steps {
                echo 'Deploying using tomcat'
            }
        }
    }
}
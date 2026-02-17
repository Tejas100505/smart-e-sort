pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project using Maven'
                bat 'mvn clean install'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful'
            }
        }

    }
}

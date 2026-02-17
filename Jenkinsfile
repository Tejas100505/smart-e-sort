pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project using Maven'
                sh 'mvn clean install'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/rajasekhar-devops/jenkins-demo-minimal.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean '
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}

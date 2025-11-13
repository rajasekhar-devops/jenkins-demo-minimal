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
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
    }
}

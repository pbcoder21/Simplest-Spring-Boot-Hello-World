pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                git 'https://github.com/pbcoder21/Simplest-Spring-Boot-Hello-World.git'
            }
        }
        stage('Maven Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Maven Build') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Maven Deploy') {
            steps {
               echo "Deploying .war to Server"
            }
        }
    }
}

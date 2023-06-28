pipeline {
    agent any

    environment {
        registry = "58605727529.dkr.ecr.us-east-1.amanonaws.com/docker-springboot"
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/deepesh-thoduvayil/docker-spring-boot']])
            }
        }
 
    }
}

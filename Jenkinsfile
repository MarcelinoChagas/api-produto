pipeline {
    agent any

    stages {
        stage ('Build Image'){
            steps{
                script{
                    dockerapp = docker.build("marcelinochagas/api-produto",'-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}
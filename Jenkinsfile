pipeline{
    agent any
    tools{
        maven "maven"
        jdk "java8"
    }
    stages{
        stage('clone'){
            steps{
                git 'https://github.com/chatwithruben/dooodap.git'
            }
        }
        stage('build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}

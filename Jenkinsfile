pipeline{
    agent none
    stages{
        stage('Example Build'){
            agent{docker 'maven:3-alpine'}
            steps{
                echo 'hello, Maven'
                sh 'mvn --version'
            }
        }
        stage('Example Test'){
            agent{docker 'openjdk:8-jre'}
            step{
                echo 'Hello, JDK'
                sh 'jave -version'
            }
        }

    }
}
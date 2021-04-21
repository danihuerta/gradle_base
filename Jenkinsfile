pipeline {
    agent any
    stages {
        stage('Unit & Integration Test'){
            steps {
                sh './gradlew clean test --no-daemon'
            }
        }
        stage('build'){
            steps{
                sh './gradlew build'
            }
        }
    }
}
@Library('my-shared-library') _
pipeline {
    agent any

    stages {
        stage('Greetings') {
            steps {
                helloWorld()
            }
        }
        stage('Build with maven'){
            steps {
                mavenBuild()
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh './mvnw clean compile'
            }
        }
    }
}
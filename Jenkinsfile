pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-17' } }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}

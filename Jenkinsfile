pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-windowsservercore' } }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}

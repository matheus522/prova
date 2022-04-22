pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'echo "Starting pipeline"'
                bat 'mvn --version'
                bat 'mvn clean'
                bat 'mvn package'
            }
        }
    }
}

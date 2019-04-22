pipeline {
    agent any
    stages {
        stage('Build') {
            sh 'mvn clean install -B -e -DskipTests = true'
        }
    }
}
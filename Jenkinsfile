pipeline {
    agent any
    stages {
        stage('Clean and Install') {
            steps {
               bash 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               bash 'mvn package'
            }
        } 
    }
}

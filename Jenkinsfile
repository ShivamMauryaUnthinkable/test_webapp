pipeline {
    agent any
    stages {
        stage('Clean and Install') {
            steps {
               /usr/bin/bash 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
               /usr/bin/bash 'mvn package'
            }
        } 
    }
}

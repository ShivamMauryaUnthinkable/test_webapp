pipeline {
    agent any
    stages {
        stage('Clean and Install') {
            steps {
               sh '''#!/bin/bash echo $PWD''' 
               sh '''#!/bin/bash mvn clean install'''
            }
        }
        stage('Package') {
            steps {
                sh '''#!/bin/bash mvn package'''
            }
        } 
    }
}

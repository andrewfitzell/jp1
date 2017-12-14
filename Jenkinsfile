#!/usr/bin/env groovy

pipeline {
    agent { /usr/local/bin/docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

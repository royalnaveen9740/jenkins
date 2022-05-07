#!/usr/bin/envgroovy

pipeline {
    agent any

    stages {
        stage('Deploy') {
            when {
              expression {
                currentBuild.result == null || currentBuild.result == 'SUCCESS' 
              }
            }
            steps {
                sh "echo This build is success"
            }
        }
    }
}
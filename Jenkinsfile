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
        }
    
            steps {
                    sh 'echo job is successfull'
                }
        }
        stage('Condition') {
            if (env.BRANCH_NAME == 'master'){
                echo 'Executed from master branch and job is sucessfull'}
            else {
                echo 'Neither code is executed from master branch nor job is successfull'
            }
        
    }
}
#!/usr/bin/envgroovy
pipeline {
    agent any 
 
    stages {
        stage('Build') {
            steps {
                echo 'Building..!' 
            }
        }
        stage('Test'){
            steps{
                echo 'Testing..'
            }
        }
        stage('Deploy'){
            step {
                echo 'Deploying..'
            }
        }
    }
}
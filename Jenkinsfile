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
                echo 'Testing..!'
            }
        }
        stage('Test 2'){
            steps{
                echo 'Testing 2..!'
            }
        }
        stage('Deploy'){
            step {
                echo 'Deploying..!'
            }
        }
    }
}
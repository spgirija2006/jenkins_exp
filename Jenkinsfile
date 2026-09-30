pipelin{
  agent any {
    stages{
      stage('checkout'){
        steps{
          checkout scm
        }
      }
       stage('Build'){
        steps{
          bat "echo building"
        }
      }
       stage('Testing'){
        steps{
         bat "echo testing"
        }
      }
        stage('deploy'){
        steps{
         bat "echo deploying"
        }
      }  stage('verifying'){
        steps{
         bat "verified"
        }
      }

pipeline {
  agent any

  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/maikynata/node-app-with-jenkins.git'
      }
    }
        
    stage('Install Dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Test Script') {
      steps {
         sh './script/test'
      }
    }      
  }
}
pipeline {
  agent any

  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/maikynata/node-app-with-jenkins.git'
      }
    }
        
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Echo Test') {
      steps {
         echo "Pipeline with Jenkinsfile"
      }
    }      
  }
}
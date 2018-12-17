pipeline {
  agent any
  stages {
    stage('sample') {
    post {
    success {
        setBuildStatus("Build succeeded", "SUCCESS");
    }
    failure {
        setBuildStatus("Build failed", "FAILURE");
          }
        }
      }
    } 
  } 

 

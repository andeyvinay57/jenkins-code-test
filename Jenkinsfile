pipeline {
  agent any
  stages {
    stage('sample') {
      steps {
        echo 'hello'
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
}
 

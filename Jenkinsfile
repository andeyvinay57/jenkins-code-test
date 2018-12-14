pipeline {
  agent any
  stages {
    stage('sample') {
      steps {
        echo 'hello'
      }
   post {
     failure {
         echo "FAIL"
       }
     }
   }
  }
}

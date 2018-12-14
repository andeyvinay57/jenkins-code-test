pipeline {
  agent any
  stages {
    stage('sample') {
      steps {
        echo 'hello'
      }
      steps {
                catchError {
                    sh './gradlew compileJava --stacktrace'
                }
            }
   
      post {
     failure {
         echo "FAIL"
       }
     }
   }
  }
}

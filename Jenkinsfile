pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
            wrap([$class: 'BuildUser']) {
            sh 'echo "${BUILD_USER}"'
         }
      }
   }
}

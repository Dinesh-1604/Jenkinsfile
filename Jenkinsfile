pipeline {
    agent any
    stages {
       stage ('Build') {
          steps {
             sh 'cp index.html /var/www/html/'
          }
       }
       stage ('Test') {
          steps {
             sh "Testing the application"
          }
       }
       stage ('Deploy') {
          steps {
             sh "deploying the application"
          }
       }
   }
}

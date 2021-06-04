pipeline {
    agent any
    stages {
       stage ('Build') {
          steps {
             sh "cp index.html /var/www/html"
          }
       }
       stage ('Test') {
          steps {
             sh "testing the application...."
          }
       }
       stage ('deploy') {
          steps {
             sh "deploying the application...."
          }
       }
   }
}

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
             echo "Testing the application"
          }
       }
       stage ('Deploy') {
          steps {
             echo "Deploying the application"
          }
       }
   }
}

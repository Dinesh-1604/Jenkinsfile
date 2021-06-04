pipeline {
    agent any
    stages {
       stage ('Build') {
          steps {
             sh """
              cp simple.java /var/www/html/
              javac /var/www/html/simple.java
              cd /var/www/html
              java simple
              """
          }
       }
       stage ('Test') {
          steps {
             echo "Testing the application..."
          }
       }
       stage ('Deploy') {
          steps {
             echo "Deploying the application"
          }
       }
   }
}

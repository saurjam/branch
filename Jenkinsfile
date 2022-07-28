pipeline {

agent any

stages {

 stage ("copy index") {

  steps {
  sh "cp -r index.html /var/www/html"
                  }
         }
 stage ("two") {
  
 steps {
 sh "cp -r dev.html /var/www/html"
              }
 }
     }
}

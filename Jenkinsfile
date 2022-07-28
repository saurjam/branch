pipeline {

agent any

stages {

 stage ("copy index") {

  steps {
  sh "cp -r index.html /var/www/html"
                  }
stage ("two") {
 steps {
 sh "cp -r dev.html /var/www/html"
              }
}
stage ("three") {
steps {
 sh "cp -r path.html /var/www/html"
                 }
   }
stage ("four") {
steps {
sh "service httpd restart"
               }
}
stage ("five"){
steps {
sh "chmod -R 777 /var/www/html/"
               }
}
         }
     }
}


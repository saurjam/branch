pipeline {

agent any

   stages {

 stage ('copy index') {

  steps ('one') {
  sh 'cp -r index.html >> /var/www/html'
                  }
stage {
 steps ('two'){
 sh 'cp -r dev.html >> /var/www/html'
              }
}
Stage { 
steps ('three') {
 sh 'cp -r path.html >> /var/www/html'
                 }
   }
stage {
steps ('four') {
sh 'service httpd restart '
               }
}
stage {
steps ('five') {
sh 'chmod -R 777 /var/www/html/'
               }
}
         }
     }
}

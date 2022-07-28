Pipeline {

agent any

   stages {

 stage ('copy index') {

  steps ('one') {
  sh 'cp -r index.html >> /var/www/html'
                  }
 steps ('two'){
 sh 'cp -r dev.html >> /var/www/html'
              }
 steps ('three') {
 sh 'cp -r path.html >> /var/www/html'
                 }
steps ('four') {
sh 'service httpd restart '
               }
steps ('five') {
sh 'chmod -R 777 /var/www/html/'
               }
         }
     }
}

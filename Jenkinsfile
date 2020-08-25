pipeline {
   agent any
     
   stages {
      stage('build master') {
          when { 
            barnch 'master'
           }
          
         steps {
            echo 'Hello master '
         }
         
         stage('build dev') {
          when { 
            barnch 'dev'
           }
          
         steps {
            echo 'Hello dev'
         }
      }
   }
}

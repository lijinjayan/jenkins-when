pipeline {
   agent any
     
   stages {
      stage('build master') {
          when { 
            branch 'master'
           }
          
         steps {
            echo 'Hello master '
         }
         
         stage('build dev') {
          when { 
            branch 'dev'
           }
          
         steps {
            echo 'Hello dev'
         }
      }
   }
}

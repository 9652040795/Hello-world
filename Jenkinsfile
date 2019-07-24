pipeline {
   agent any
   stages {
      stage('Scm Checkout') {
         steps {
            git 'https://github.com/javahometech/my-app'
         }
      
      }
         steps {
           withMaven(maven : 'maven') {
           sh 'mvn package'
           }          
         }
   }
}
                          
                     
        

pipeline {
   agent any
   stages {
      stage('Scm Checkout') {
         steps {
            git 'https://github.com/9652040795/Hello-world'
         }
      
      }
         steps {
           withMaven(maven : 'maven') {
           sh 'mvn package'
           }          
         }
   }
}
                          
                     
        

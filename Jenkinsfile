pipeline {
   agent any
   stages {
      stage('compile_code') {
             steps {
                  withMaven(maven : 'maven') {
                  sh 'mvn package'
                  }          
             }
      }
}
   
}   
                          
                     
        

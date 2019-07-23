node{
   stage('Scm Checkout') {
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-package'){
      def mavenHome = tool name: 'maven', type: 'maven' 
      sh "${mavenHome}/opt/apache-maven-3.6.0/mvn package"
   }
   
}
                        
                          
                     
        

node{
   stage('Scm Checkout') {
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-package'){
      def mvnHome = tool name: 'maven-3', type: 'maven'
      sh "${mvnHome}/opt/mvn package"
   }
   
}
                        
                          
                     
        

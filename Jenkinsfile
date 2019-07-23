node{
   stage('Scm Checkout') {
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-package'){
      def mvnHome = tool name: 'maven', type: 'maven' 
      sh "${mvnHome}/opt/mvn package"
   }
   
}
                        
                          
                     
        

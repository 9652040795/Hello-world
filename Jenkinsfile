pipeline {
        agent any
                stages {
                        stage('One') {
                                steps {
                                        echo 'Hi, This is my first pipeline'                                     
                                }
                        }
                        stage('Two') {
                                steps {
                                        input('Do you want to proceed?')
                                }
                        }
                        stage('Three') {
                                steps {
                                       echo "Hello"
                                }    
                        }
                        stage('Four') {
                                        
                                steps {
                                       echo "Running the unit test"
                                }   
                                              
                        }



}

}
        

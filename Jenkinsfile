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
                                when {
                                       not {
                                             branch 'master'
                                       }
                                }
                                steps {
                                       echo "Hello"
                                }    
                        }
                        stage('Four') {
                                        parallel {
                                              stage('Unit Test') {
                                                                  echo "Running the unit test"
                                              }      
                                        }      
                        }



}

}
        

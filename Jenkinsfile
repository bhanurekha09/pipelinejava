pipeline{
          agent none
           stages {
                     
                     stage ( 'STAGE 1' )  {
                     agent { label 'jenkin-slave2' }
                      steps {
                               git 'https://github.com/bhanurekha09/csource.git'
                               sh 'make'
                               echo "**********************"
                               sh 'sleep 10'
                               
                             }
                    }
                     
                     
                     
                   
                    stage ( 'STAGE 2' )  {
                    agent { label 'jenkin-slave1' }
                    steps {
                               git 'https://github.com/bhanurekha09/java.git'
                               sh 'mvn clean install'
                               echo "**********************"
                               sh 'sleep 10'
                               
                         }
                    }
           }
        
        
}
        
                    
        

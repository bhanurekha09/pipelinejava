pipeline{
          agent none
           stages {
                     
                     stage ( 'STAGE 1' )  {
                     agent { label 'jenkin-slave2' }
                  steps {
                               git 'https://github.com/bhanurekha09/java.git'
                               sh 'make'
                               echo "**********************"
                               sh '10'
                         }
                    }
        }
        
        
}
        
                    
        

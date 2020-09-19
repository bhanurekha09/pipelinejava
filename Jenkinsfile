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
                               sh 'rmdir csource'
                         }
                    }
        }
        
        
}
        
                    
        

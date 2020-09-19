pipeline{
          agent none
           stages {
                     
                     stage ( 'STAGE 1' )  {
                     agent { label 'master' }
                  steps {
                               git 'https://github.com/bhanurekha09/java.git'
                               sh 'mvn clean install'
                               echo "**********************"
                               sh '10'
                         }
                    }
        }
        
        
}
        
                    
        

pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "myslavemaven"
            }
          
          steps {
             
                echo "my fix-123 branch"
          }
        }
   }
}

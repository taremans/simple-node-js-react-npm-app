pipeline {
  agent any
    
  tools {nodejs "Node18"}
    
  stages {
        
   
     
    stage('Build') {
      steps {
        sh 'npm install'
        
      }
    }  
    
     stage('Run') {
      steps {
        sh 'npm run dev'
        
      }
    }  
    
            
   
  }
}

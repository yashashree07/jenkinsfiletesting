pipeline{
  agent any
  tools {
        maven 'Maven_3.5.2' 
    }
  stages {
    stage('Compile Stage'){
    
          steps{
                  {
                        sh 'mvn compile'
                 }
          }
    }
    stage('Test Stage'){
            
            steps{
                   {
                        sh 'mvn test'
                  }
           }
    }
    stage('Reporting Stage'){
    
             steps{
                    {
                        sh 'mvn report'
                  }
           }
    }
  }
}
  
      
       

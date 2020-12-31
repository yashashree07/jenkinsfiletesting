pipeline{
  agent any
  tools {
        MAVEN_HOME 'apache-maven-3.6.3' 
    }
  stages {
    stage('Compile Stage'){
    
          steps{
                  
                        sh 'mvn compile'
                 
          }
    }
    stage('Test Stage'){
            
            steps{
                   
                        sh 'mvn test'
                  
           }
    }
    stage('Reporting Stage'){
    
             steps{
                    
                        sh 'mvn report'
                  
           }
    }
  }
}
  
      
       

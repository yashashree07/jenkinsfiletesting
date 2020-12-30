pipeline{
  agent any
  
  stages {
    stage('Compile Stage'){
    
          steps{
                   withMaven(maven : 'maven-3.6.3'){
                        sh 'mvn compile'
                 }
          }
    }
    stage('Test Stage'){
            
            steps{
                    withMaven(maven : 'maven-3.6.3'){
                        sh 'mvn test'
                  }
           }
    }
    stage('Reporting Stage'){
    
             steps{
                    withMaven(maven : 'maven-3.6.3'){
                        sh 'mvn test'
                  }
           }
    }
  }
}
  
      
       

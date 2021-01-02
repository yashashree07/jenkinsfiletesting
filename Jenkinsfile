pipeline { 
    agent any  
    stages { 
        stage('Checkout') { 
            
               git branch: 'main', url: 'https://github.com/yashashree07/jenkinsfiletesting.git'
            
        }
        stage('build') { 

               def mavenhome= tool name: 'MAVEN_HOME', type: 'maven'
                sh "${mavenhome}/bin/mvn test"
            
        }
    }
}

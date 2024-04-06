pipeline {
    agent any 
    stages {
        stage('checkout scm')
        {
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'pass1', url: 'https://github.com/sumit9090/helloword.git']])
            }
        }
        
        
    }
    
    
}

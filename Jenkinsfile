pipeline {
    agent { label 'test' }

    
    stages {
        stage('Pull Git content') {
            steps {
       
                
                sh 'mkdir -p /as2'
                sh 'cp -r file1.txt file2.txt tada /as2'
            }
        }
        
    }
}    
   

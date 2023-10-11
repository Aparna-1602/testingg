pipeline {
    agent { label 'test' }

    
    stages {
        stage('Pull Git content') {
            steps {
                git branch: 'test', credentialsId: 'dbb24d25-de79-4093-9aa7-ac9f364e76fb', url: 'https://github.com/Aparna-1602/testingg.git'
                
                sh 'mkdir -p /as2'
                sh 'cp -r file1.txt file2.txt  /as2'
            }
        }
        
    }
} 

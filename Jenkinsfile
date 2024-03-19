pipeline{
    agent any
    stages{
        stage("git Checkout"){
            steps{
                 git url: 'https://github.com/vignesh810/microservice.git', branch: 'main'
                 sh 'ls -l'
            }
            }
        stage("Build and test"){
            steps{
                sh "mvn clean install"
            }
        }
            
        
    }    
    
        }

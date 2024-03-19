pipeline{
    agent any
    stages{
        stage("Clean working directory"){
            cleanws()
        }
        stage("git Checkout")
            {
                 git url: 'https://github.com/vignesh810/microservice.git', branch: 'main'
                 sh 'ls -l'
            }
       
        
        
    }    
    
        }

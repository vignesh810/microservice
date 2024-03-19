pipeline{
    agent any
    stages{
        stage("Clean working directory"){
            cleanws()
        }
        stage("git Checkout")
        {
            dir ("$WORKSPACE/eks-project/microservice\")
            {
                 git url: 'https://github.com/vignesh810/microservice.git', branch: 'main'
                 sh 'ls -l'
            }
        }   
        
        
    }    
    
        }

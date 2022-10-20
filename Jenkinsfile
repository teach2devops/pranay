pipeline{
    agent any
    stages{
        stage("install package"){
            steps{

                sh 'sudo yum install httpd -y'

            }
            
        }
    
        stage("start service"){
            steps{

                sh 'sudo systemctl start httpd'


            }
            
        }
        stage("Deploy stage"){
            steps{

                sh 'sudo cp * /var/www/html/'


                
            }
            
        }
        
    }

}


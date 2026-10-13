pipeline{
   agent any
   stages{
     stage(""){
        steps{
           sh '''
                 apt update -y
                 apt upgrade -y
                 apt install vim sudo docker.io docker-compose -y
            '''
        }
     }
   }
}

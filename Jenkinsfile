pipeline{

agent any

stages{

        stage('stage getting from my branch'){
                steps{
				     sleep 10
					 echo 'I slept for 10 seconds till now'
					 echo 'Iam going sleep for next 10 min and please go there and make changes in git on my branch'
					 sleep 600
					 echo 'It is getting done now'
					 
                    git url:'https://github.com/Samala123/js-e2e-express-server.git' , branch:'branch_l1'
					echo 'Please go there and check it out buddy'
					} //steps
             
			 
            }
			}
      
        }//pipeline
		
		
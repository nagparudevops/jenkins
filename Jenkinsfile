pipeline {
    agent 
    {
        node {
            label "ROBOSHOP"
        }
        stages{
            stage('build') 
            {
                steps {
                    echo "building..!!!"
                }
            }
        
            stage('Test') 
            {
                steps {
                    echo "Testing..!!!"
                }
            }
           
        stage('deploy') 
            {
                steps {
                    echo "deploying..!!!"
                }
            }
        }    
        
    }
}
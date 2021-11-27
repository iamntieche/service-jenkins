pipeline{
    agent any

    stages{
        stage('COMPILE'){
             steps{
                script{
                    last_started = 'service-jenkins';              
                    sh "mvn clean install";
                    echo "$last_started Passed successfully!!";  
                }
                
            }
        }
    }
}
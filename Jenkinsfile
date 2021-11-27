pipeline{
    agent any  
    stages{
        stage('Quality Gate Statuc Check){
           agent {
            docker {
                image 'maven'
                }
            }
        }
    }
}
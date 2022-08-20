pipeline{
    //agent any
    agent {label 'slave'}
    stages{
        stage('Git Pull'){
            steps{
                sh "start of stage 1"
            }
        }
        stage('Build and Push'){
            steps{
                sh "start of stage2"
            }
            
        }
    }
}

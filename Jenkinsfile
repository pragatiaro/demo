pipeline{
    //agent any
    agent {label 'slave'}
    stages{
        stage('Git Pull'){
            steps{
                sh "echo hello"
                sh "echo hi again"
            }
        }
        stage('Build and Push'){
            steps{
                sh "start of stage2"
            }
        stage('Deployment'){
            steps{
                sh "echo deployment"            
            }
        }

        }
    }
}

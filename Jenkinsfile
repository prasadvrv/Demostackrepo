pipeline {
    agent any
    triggers {
         pollSCM('* * * * *')
     }
    stages{
        stage('Checkout'){
            steps {
                checkout scm
            }
        }
        stage('Build'){
            steps {
                sh 'sh demoscript'
            }
        }
    }
}    

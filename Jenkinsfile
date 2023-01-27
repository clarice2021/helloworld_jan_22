pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Build step'
                sleep 10
            }   
        }
        stage('Test'){
            steps {
                echo 'Test stest'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploy step'
                sleep 10
            }
        }
        stage('Docker'){
            setps{
                echo 'Image step'
            }
        }
    }
}

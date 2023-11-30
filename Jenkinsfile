pipeline{
    agent any

    stages{
        stage('STAGE INSTALACAO NPM'){
            steps{
                sh '''

                npm install 

                '''
            }

        }
        stage('STAGE TESTE'){
            steps{
                sh '''

                npm test 

                '''
            }
            
        }
        stage('STAGE DOCKER'){
            steps{
                sh '''

                docker build

                '''
            }
        }
        stage('STAGE DOCKER'){
            steps{
                sh '''

                docker compose up 

                '''
            }
            
        }
    }
}
pipeline {
    agent any

    stages {
      
        stage('change dir') {
            steps {
                dir('the-example-app.nodejs') {
                // some block
                }
            }

        }
        stage('npm install') {
            steps {
                bat '''npm install
                '''
            }

        }
        stage('npm run') {
            steps {
                bat '''npm run
                '''
            }

        }
        stage('pm2 install') {
            steps {
                bat '''npm install pm2
                '''
            }

        }
        stage('pm2 start') {
            steps {
                bat 'pm2 start app.js'
            }

        }
        
    
    }


}

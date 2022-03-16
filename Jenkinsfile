pipeline {
    agent any

    stages {
        stage('npm install') {
            steps {
                npm install
                
            }

        }
        stage('pm2 install') {
            steps {
                npm 'npm install pm2'
            }

        }
        stage('pm2 start') {
            steps {
                npm 'pm2 start app.js'
                
            }

        }

    
    }


}

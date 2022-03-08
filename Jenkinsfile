pipeline {
    agent any

    stages {
      
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
    
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }
    
        stage('Deploy') {
            steps {
                echo 'Deploy App'
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
        
        stage('pm2 list') {
            steps {
                bat '''pm2 list
                '''
            }

        }
    
    }


}

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
        stage('npm') {
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
    
    }


}

pipeline { 
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building application from Github...'
            }
        }
        stage('Test'){
            steps {
                echo 'Running automated tests...'
            }   
        }
        stage('Deploy') {
            steps {
                echo 'Deploying  application...'
            }
        }
    }
}

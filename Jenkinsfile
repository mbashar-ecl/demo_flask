pipeline{
    agent any 
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}

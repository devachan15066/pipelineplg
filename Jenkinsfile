pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Add your build steps here
                sh 'echo "Building..."'
            }
        }
        
        stage('Test') {
            steps {
                // Add your test steps here
                sh 'echo "Testing..."'
            }
        }
        
        stage('Deploy') {
            steps {
                // Add your deployment steps here
                sh 'echo "Deploying..."'
            }
        }
    }
    
    post {
        success {
            // Actions to perform when the pipeline succeeds
            sh 'echo "Pipeline succeeded!"'
        }
        
        failure {
            // Actions to perform when the pipeline fails
            sh 'echo "Pipeline failed!"'
        }
        
        always {
            // Actions to perform regardless of pipeline result
            sh 'echo "Pipeline finished!"'
        }
    }
}

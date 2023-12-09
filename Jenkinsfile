pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                script{
                    echo "Current branch: ${env.BRANCH_NAME}"
                    echo "Current directory: ${pwd()}"
                    sh 'ls'
                }
            }
        }
    }
}

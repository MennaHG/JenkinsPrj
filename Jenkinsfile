pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                script {
                    echo "Current directory: ${pwd()}"
                    sh 'ls'
                }
            }
        }
    }
}

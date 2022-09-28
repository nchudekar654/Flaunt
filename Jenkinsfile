pipeline {
    agent any
    
    tools {nodejs '14.17.5'}

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}

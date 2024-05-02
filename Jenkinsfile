pipeline {
    gent {
        docker {
            image 'node:18-alpine'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}


pipeline {
agent {
    docker { image 'node:22.1-alpine3.19' }
  }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}


pipeline {
    agent { 
        docker { 
            image 'python:3-alpine'
        } 
    }
    stages {
        stage('Build') {
            steps {
                sh 'python3 run.py'
             
            }
        }
      
    }
}

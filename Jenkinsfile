pipeline {
    agent {
        docker {
            image 'docker.io/httpd:latest'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'docker run -itd docker.io/httpd:latest /bin/bash' 
            }
        }
    }
}

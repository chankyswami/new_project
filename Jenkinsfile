pipeline {
    agent {
        docker {
            image 'docker pull httpd:latest'
            echo "Image selected"
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

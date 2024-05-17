pipeline {
    agent {
        docker {
            image '192.168.241.161:8083/docker-private-evaluation/jenkinsslavemaven'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

pipeline {
    agent {
        label 'jenkinsslavemaven'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

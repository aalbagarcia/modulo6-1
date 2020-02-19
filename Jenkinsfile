pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'make'
            }
        }
        stage('Run') {
            steps {
                sh './a.out'
            }
        }
    }

    post {
        always {
            chuckNorris
        }
    }
}
pipeline {
    agent { docker { label: 'test1' } }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
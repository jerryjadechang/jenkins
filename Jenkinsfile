pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('Sanity check') {
            steps {
                input "Does the staging environment look ok?"
            }
        },
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

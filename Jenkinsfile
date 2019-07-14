pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        
        stage('Sanity check') {
            steps {
                input "Does the staging environment look ok?"
            }
        }
        
        stage('Test') {
            steps {
                sh 'cat /home/Documents/foobar'
            }
        }
        
    }
}

pipeline {
    agent any

    stages {
        stage('Credential Scan') {
            steps {
                sh 'gitleaks dir --verbose .'
            }
        }
    }
}

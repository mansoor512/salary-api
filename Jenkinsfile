pipeline {
    agent any

    stages {
        stage('Credential Scan') {
            steps {
                sh 'cat test-secret.txt'
                sh 'gitleaks detect --source . --verbose'
            }
        }
    }
}

pipeline {
    agent any

    environment {
        TEST_CREDENTIALS = credentials('TEST_CREDENTIALS')
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo "Test credentials: ${TEST_CREDENTIALS}"'
            }
        }
    }
}

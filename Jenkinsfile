pipeline {
    agent any

    stages {
        stage('Force Fail') {
            steps {
                sh 'echo "TEST JENKINS"'
                sh 'exit 1'
            }
        }
    }
}

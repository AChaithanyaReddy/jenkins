pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo build step"
            }
        }
        stage('Test') {
            steps {
                sh "echo test step"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo deploy step"
            }
        }
    }

    post {
        always{
            echo "This section runs always"
        }
        success{
            echo "This section run when pipeline success"
        }
        failure{
            echo "This section run when pipeline failure"
        }
    }
}
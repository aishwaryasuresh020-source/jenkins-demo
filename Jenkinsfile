pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building from Jenkinsfile'
            }
        }
    }

    post {
        success {
            echo 'Build Successful!'
        }
        failure {
            echo 'Build Failed!'
        }
    }
}

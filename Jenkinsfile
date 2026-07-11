pipeline {
    agent { label 'electronix' }

    stages {
        stage('Build') {
            steps {
                echo "Build java application"
            }
        }

        stage('Test') {
            steps {
                echo "Test application"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy application on server"
            }
        }
    }

    post {
        success {
            echo "Pipeline Pass"
        }

        failure {
            echo "Pipeline Fail"
        }
    }
}

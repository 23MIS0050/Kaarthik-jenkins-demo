pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from Git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESS: All stages executed successfully'
        }
        failure {
            echo 'BUILD FAILURE: Something went wrong'
        }
    }
}

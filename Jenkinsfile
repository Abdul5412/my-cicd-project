pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build is running'
                sh 'oc version --client'
            }
        }

        stage('Test') {
            steps {
                echo 'Test is running'
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy is running'
            }
        }
    }
}

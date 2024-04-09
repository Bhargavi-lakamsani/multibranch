pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               echo 'checkout stage is first stage' 
            }
        }

        stage('Build') {
            steps {
                echo 'build stage is second stage'
            }
        }

        stage('Push') {
            steps {
                echo 'push stage is third stage'
            }
        }

        stage('Deploy') {
            steps {
                echo 'deploy is fourth stage and last stage'
            }
        }

    }

}

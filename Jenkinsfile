pipeline {
    agent none
    stages {

        stage('Building Hello Jenkins') {
            steps {
                echo 'Hello Jenkins!'
            }
        }

        stage('Building second stage to test GitHub Webhook') {
            steps {
                echo 'This is the second push, it should trigger a build!'
            }
        }
    }
}
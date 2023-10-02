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
                echo 'This is the second push, it did not trigger a build'
                echo 'Neither did the test ping by GitHub.'
            }
        }

        stage('Building a third stage') {
            steps{
                echo 'Second try at triggering via WebHook.'
            }
        }
        
        stage('Building a fourth stage') {
            steps{
                echo 'Went into Jenkins configurations to allow a WebHook from GitHub after a push.'
            }
        
        stage('Building a fifth stage') {
            steps{
                echo 'Went into GitHub configurations to llow a change the URL of where thr repo pushed to in Jenkins.'
            }

    }
}
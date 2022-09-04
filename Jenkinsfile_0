pipeline {
    agent any
    
    stages {
        stage('Test') {
            steps {
                echo 'Hello Test'
                slackSend channel: "#jenkins", color: "good", message: "Message test"
            }
        }
        stage('Build') {
            steps {
                echo 'Hello World'
                slackSend channel: "#jenkins", color: "good", message: "Message build"
            }
        }
    }
}
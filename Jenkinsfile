pipeline {
    agent {
        node {
            label "windows && java11"
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo("Hello Pipeline")
            }
        }
    }

    post {
        always {
            echo "Always Say Hello"
        }
        success {
            echo "Success"
        }
        failure {
            echo "Failure"
        }
        cleanup {
            echo "Clean Up"
        }
    }
}
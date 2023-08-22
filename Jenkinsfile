pipeline {
    agent {
        node {
            label "windows && java11"
        }
    }
    stages {
        stage("Build") {
            steps {
                echo("Stage Build")
            }
        }
        
        stage("Test") {
            steps {
                echo("Stage Test")
            }
        }
        
        stage("Deploy") {
            steps {
                echo("Stage Deploy")
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
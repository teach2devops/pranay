pipeline {
    agent any
    
    stages {
        stage("Build") {
            steps {
                echo "Build stage."
                echo "Hello $params.TEST_STRING"
            }
        }
        stage("Test") {
            steps {
                echo "Test stage."
            }
        }
        stage("Release") {
            steps {
                echo "Release stage."
            }
        }
    }
}
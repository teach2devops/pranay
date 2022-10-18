pipeline {
    agent any
    stages {
        stage('OS Version') {
            steps {
                sh 'cat /etc/*release'
            }
        }
        stage('Package Instalaltion') {
            steps {
                sh 'mkdir /tmp/amazon'
            }
        }
    }
}
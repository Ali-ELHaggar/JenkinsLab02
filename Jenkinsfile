pipeline {
    agent any

    stages {
        stage("prepare") {
            steps {
                echo "preparing your code"
            }
        }
        
        stage('check') {
            steps {
                echo "checking your code"
            }
        }

        stage('test') {
            steps {
                echo "testing your code"
            }
        }
        
        stage('deployment') {
            steps {
                echo "your code is deployed right now"
                echo "this build number $BUILD_NUMBER"
            }
        }
    }
}

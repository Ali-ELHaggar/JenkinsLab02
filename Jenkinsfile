pipeline {
     agent any
    }

    stages {
         stage("Clone Git Repository") {
            steps {
                git(
                    url: "https://github.com/ssbostan/neptune.git",
                    branch: "master",
                    changelog: true,
                    poll: true
                )
            }
        }
        stage('check') {
            steps {
                echo "checking your code"
               
            }
        }

        stage('test') {
          echo "testing your code your code"  
        }
        
        stage('deployment') {  
            steps {
                echo "your code is deployed right now"
                echo "this build number $BUILD_NUMBER"
            }
        }    
    }

}

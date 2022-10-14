pipeline {
    agent any
       stages {
        stage("Application Sync") {
            steps {
                 sh """
                 aws --version
          chmod +x script.sh
          ./script.sh    
                }
            }
        }
    }

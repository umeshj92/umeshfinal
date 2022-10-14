pipeline {
    agent any
       stages {
        stage("Application Sync") {
            steps {
                 sh '''
                 chmod +x script.sh
          ./script.sh
                }
            }
        }
    }

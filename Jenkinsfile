pipeline {
    agent any
    environment{
         def toolbelt = tool 'sfdx'
    }
    stages {
        stage('Build') {
     
            steps {
                script{
                    bat '%toolbelt%/sfdx force help'
                }
            }
        }
    }
}


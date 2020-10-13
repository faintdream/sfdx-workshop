pipeline {
    agent any
    environment{
         def toolbelt = tool 'sfdx'
    }
    stages {
        stage('runitbro') {
     
            steps {
                script{
                    bat '%toolbelt%/sfdx force --help'
                }
            }
        }
    }
}


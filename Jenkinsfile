pipeline {
    agent any
    environment{
         def toolbelt = tool 'sfdx'
    }
    stages {
        stage('run_help_bro') {
     
            steps {
                script{
                    bat '%toolbelt%/sfdx force --help'
                }
            }
        }
    }
}


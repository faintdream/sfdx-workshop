pipeline {
    agent any
    stages {
        stage('Build') {
            def toolbelt = tool 'sfdx'
            steps {
                script{
                    bat '${toolbelt} force help'
                }
            }
        }
    }
}


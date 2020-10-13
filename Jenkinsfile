pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    bat '${sfdx} force help'
                }
            }
        }
    }
}


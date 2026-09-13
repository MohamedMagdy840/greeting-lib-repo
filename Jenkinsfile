@Library('jenkins-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Send Greeting') {
            steps {
                // Call the shared library function
                greet('')
            }
        }
    }
}

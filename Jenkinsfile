@Library('greeting-lib') _

pipeline {
    agent any
    stages {
        stage('Send Greeting') {
            steps {
                // Call the shared library function
                greet('You are doing great, keep learning!')
            }
        }
    }
}

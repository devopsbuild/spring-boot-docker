pipeline {
    agent any
    stages {
        stage ('build') {

            steps {
                withMaven(maven : 'apache-maven') {
                    bat 'mvn clean install'
                }
            }
        }
    }
}
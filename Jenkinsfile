pipeline{
    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install sonar:sonar'
            }
        }
    }
}
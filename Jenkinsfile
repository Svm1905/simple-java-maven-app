 
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "mvn clean"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
              sh "mvn test"
            }
        }
        stage('Compile') {
            steps {
                echo 'Compiling....'
              sh "mvn compile"
            }
        }
    }
}

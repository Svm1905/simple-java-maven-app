 
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
               withMaven(maven: 'mvn') {
            sh "mvn clean package"
        }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
              withMaven(maven: 'mvn') {
            sh "mvn clean package"
        }
            }
        }
        stage('Compile') {
            steps {
                echo 'Compiling....'
              withMaven(maven: 'mvn') {
            sh "mvn clean package"
        }
            }
        }
    }
}

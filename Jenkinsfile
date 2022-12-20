pipeline {
    agent any

    stages {
        stage('Build & Test') {
            steps {
                echo 'Building..'
                sh './gradlew clean build'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying..'
            }
        }

    }
}
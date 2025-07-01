pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Mohankandi/Jenkins-Demo.git'

            }
        }
        stage('Build') {
            steps {
                echo 'Building from GitHub...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}

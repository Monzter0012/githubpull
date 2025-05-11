pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git url: 'https://github.com/Monzter0012/githubpull', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Pretend we are testing something here"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project (dummy step)...'
            }
        }
    }
}

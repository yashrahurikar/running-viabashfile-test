pipeline {
    agent any
    stages {
        stage('Testing stage') {
            steps {
                echo 'Testing'

            }
        }
        stage('Build') {
            steps {
                echo 'Building'
                sh 'yarn add package.json'
                sh 'yarn build'
            }
        }
    }
}

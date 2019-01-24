pipeline {
    agent any
    stages {
        stage('Testing stage') {
            steps {
                echo 'Testing'
                sh 'source test.sh'
                sh '_test_func'
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

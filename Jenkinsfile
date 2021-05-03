pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                build quietPeriod: 5, job: 'DemoJob2'
            }
        }
    }
}

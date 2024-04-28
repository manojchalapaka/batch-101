pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                 build quietPeriod: 5, job: 'job7'
            }
        }
        stage('job') {
            steps {
                echo 'Hello job'
                build quietPeriod: 5, job: 'Test1'
                
            }
        }
    }
}

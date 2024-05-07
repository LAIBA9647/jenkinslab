pipeline {
    agent any

    stages{
        stage ('build') {
            steps {
                sh 'npm install'
            }
        }


        stage ('test') {
            steps {
                sh 'echo "test running"'
            }
        }


        stage ('deploy') {
            steps {
                sh 'echo "deploying the app"'
            }
        }



    }
}
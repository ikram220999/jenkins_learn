pipeline {
    agent any
    environment {
        NEW_VERSION = "1.2.0"
    }
    stages {
        stage('build') {
             steps {
                echo 'building app ...'
                // double quote to put variable
                ehco "app version ${NEW_VERSION}"
            }
        }
        stage('test') {
            steps {
                echo 'testing app ...'
            }
        }
        stage('deploy') {
             steps {
                echo 'deploying app ...'
            }
        }
    }
    post {
        // always {
        //     echo 'Done ...'
        // }
        // successs {
        //     echo 'Success ...'
        // }
        // failure {
        //     echo 'Fail ...'
        // }
    }
}
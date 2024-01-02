pipeline {
    agent any
    stages {
        stage('first stage') {
            steps {
                sh "cat /var/lib/jenkins/jobs/projects/dev/sample.sh"
            }
        }
        stage('second stage') {
            steps {
                echo 'Succesfully deployed the first stage'
            }
        }
    }
}
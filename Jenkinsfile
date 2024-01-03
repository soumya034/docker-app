pipeline {
    agent any
    parameters {
        choice(name: 'ENVIRONMENT', choices: ['dev', 'qa', 'prod'], description: 'Select the deployment environment')
    }
    stages {
        stage('first stage') {
            steps {
                echo "${params.ENVIRONMENT}: environment completed"
            }
        }
	stage('second stage') {
            steps {
                echo "${params.ENVIRONMENT.choice[1]}: environment completed"
            }
        }
    }
}
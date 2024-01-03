pipeline {
    agent any
    parameters {
        choice(name: 'CHOICE_PARAMETER', choices: ['dev', 'qa', 'prod'], description: 'Select the deployment environment')
    }
    stages {
        stage('first stage') {
            steps {
                echo "${params.CHOICE_PARAMETER}: environment completed"
            }
        }
	stage('second stage') {
            steps {
                echo "${params.CHOICE_PARAMETER[0]}: environment completed"
            }
        }
    }
}

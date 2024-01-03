pipeline {
    agent any
    parameters {
        choice(name: 'CHOICE_PARAMETER', choices: ['dev', 'qa', 'prod'], description: 'Select the deployment environment')
    }
    stages {
        stage('first stage') {
            steps {
		script {
		def firstChoice = params.CHOICE_PARAMETER[0]
                echo "${firstChoice}: environment completed"
		}
            }
        }
	stage('second stage') {
            steps {
		script {
		def secondChoice = params.CHOICE_PARAMETER[1]
                echo "${secondChoice}: environment completed"
		}
            }
        }
    }
}

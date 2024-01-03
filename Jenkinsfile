pipeline {
    agent any
    parameters {
        choice(name: 'PARAMETER', choices: ['dev', 'qa', 'prod'], description: 'Select the deployment environment')
    }
    stages {
        stage('first stage') {
            steps {
		script {
		def firstChoice = params.PARAMETER[0]
                echo "environment completed: ${firstChoice}"
		}
            }
        }
	stage('second stage') {
            steps {
		script {
		def secondChoice = params.PARAMETER[1]
                echo "environment completed: ${secondChoice}"
		}
            }
        }
    }
}

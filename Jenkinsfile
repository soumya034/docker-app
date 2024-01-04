pipeline {
    agent any
    // parameters {
    //     choice(name: 'PARAMETER', choices: ['dev', 'qa', 'prod'], description: 'Select the deployment environment')
    // }
    stages {
        stage('first stage') {
            steps {
		script {
                echo "environment completed:"$env
		// ${params.PARAMETER}"
		}
            }
         }
	// stage('second stage') {
 //            steps {
	// 	script {
	// 	def secondChoice = params.PARAMETER[1]
 //                echo "environment completed: ${secondChoice}"
	// 	}
 //            }
 //        }
	// stage('third stage') {
 //            steps {
	// 	script {
	// 	def thirdChoice = params.PARAMETER[2]
 //                echo "environment completed: ${thirdChoice}"
	// 	}
 //            }
 //        }
    }
}

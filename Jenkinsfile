//Scripted Pipeline approch
// node {
// 	echo "Build"
// 	echo "Test"
// 	echo "Integration Test"
// 	}

//Declarative Pipeline approch
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}
}
 post {
	always {
		echo "This will always run"
	}
	success {
		echo "This will run only if the pipeline is successful"
	}
	failure {
		echo "This will run only if the pipeline fails"
	}
}
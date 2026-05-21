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
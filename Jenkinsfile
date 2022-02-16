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
	} post {
		always {
			echo "Runs always"
		}
		success {
			echo "runs when successful"
		}
		failure {
			echo "runs when a stage fails"
		}
	}
}

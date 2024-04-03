pipeline {

	agent any
	
	stages {

		stage("build"){

			steps {
				echo 'Building the application...'
				python3 main.py
			}

		}

		stage("test"){

			steps {
				echo 'Testing the application...'
			}

		}

		stage("deploy"){

			steps {
				echo 'Deploying the application...'
			}

		}
	}
}

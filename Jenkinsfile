pipeline {

	agent any
	
	stages {

		stage("build"){

			steps {
				echo 'Building the application...'				

				script {
					def test = true
					echo test
				}
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

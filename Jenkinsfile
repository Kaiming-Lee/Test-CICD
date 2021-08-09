pipeline {

	agent any
	environment {
		VERSION = '1.3.1'
		BRANCH = 'dev'
	}

	stages{

		stage("build") {

			steps {
				echo 'building the application...'
				echo 'building version is ${VERSION}'
			}
		}

		stage("test") {

			steps {
				echo 'testing the application...'
			}
		}

		stage("deploy") {

			steps {
				echo 'deploying the application...'
			}
		}
	}
}

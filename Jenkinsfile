pipeline {
	agent any
	options {
		buildDiscarder logRotator(atifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
		disableConcurrentBuilds()
	}
	stages {
		stage('Hello') {
			steps {
				echo "hello"
			}
		}
	}
}

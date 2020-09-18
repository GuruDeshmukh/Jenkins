pipeline {
	agent none 

	stages {
		stage ('STAGE 1') {
			agent { label 'master' }
			steps {
			  	sh 'sleep 20'
			}
		}
		stage ('STAGE 2') {
			agent { label 'java-1' }
			steps {
				sh 'sleep 20'
			}
		}
		stage ('STAGE 3') {
			agent { label 'java' }
			steps {
				sh 'sleep 20'
			}
		}
		stage ('STAGE 4') {
			agent { label 'java-1' }
			steps {
				sh 'sleep 20'
			}
		}
	}
}

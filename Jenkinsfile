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
			agent { label 'slave-1' }
			steps {
				sh 'sleep 20'
			}
		}
		stage ('STAGE 3') {
			agent { 'slave-2' }
			steps {
				sh 'sleep 20'
			}
		}
		stage ('STAGE 4') {
			agent { 'slave-1' }
			steps {
				sh 'sleep 20'
			}
		}
	}
}

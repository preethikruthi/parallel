pipeline {
	agent any
	stages {
		stage ('all stage') {
			parallel {
		stage {'build-check') {
			steps {
				echo 'building ...'
				sh 'sleep 100'
			}
		}
		       stage {'depoly') {
			steps {
				echo 'deploying to test environment...'
				sh 'sleep 100'
			}
		}
			      stage {'test') {
			steps {
				echo 'testing ...'
				sh 'sleep 100'
			}
		}
	
				    }
			     }
		      }
		}

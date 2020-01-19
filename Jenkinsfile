pipeline {
	agent any
	stages {
		stage ('all stage') {
			
			stage ('build-check') {
				steps {
					input ('press yes to continue')
					echo 'building'...'
					sh 'sleep 10'
				}
			}
			stage ('depoy') {   
			steps {
				echo 'deploying to test environment...'
				sh 'sleep 10'
			}
		}
			      stage ('test') {
			steps {
				echo 'testing ...'
				sh 'sleep 10'
			}
		}
	
				    }
			     }
		      }
		}

pipeline {
	agent any
	stages {
		stage ('all stage') {
			parameters {
				string (var1:parameter 1,...) 
			stage ('build-check') {
				steps {
					
					echo 'building...'
					sh 'sleep 1'
				}
			}
			stage ('depoy') {   
			steps {
				echo 'deploying to test environment...'
				sh 'sleep 1'
			}
		}
			      stage ('test') {
			steps {
				echo 'testing ...'
				sh 'sleep 1'
			}
		}
	
				    }
			     }
		      }
		}

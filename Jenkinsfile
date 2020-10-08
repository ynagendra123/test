pipeline {
	agent any 
	  stages {
			   stage('one') {
		                steps {
								echo "this is 1st stage"
							  }
							}
			   stage('two') {
						 steps {
								 echo "this is 2nd stage"
								 input('Do you want to proceed')
								}
							}
			   stage('three') {
						  steps {
								   echo "this is the 3rd stage"
								}
							  }
				}
		  }

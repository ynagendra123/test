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
								 echo "this is 2nd stage
								}
							}
			   stage('three') {
						  steps {
								   echo "this is the 3rd stage"
								}
							  }
				}
				post {
				 always {
				         echo "running always"
						}
				 success {
				        echo "the build is success"
						 }
				 failure {
						echo "the build is falied"
				         }
				    }
		  }

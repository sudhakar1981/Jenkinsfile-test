

pipeline{
	agent any
	
	stages {
		
		stage ("scm-fetch") {
			steps{
				echo 'Fetching Source Code management from GITHUB'
				sh 'sleep 10'
			}
		}
		
		stage ("build") {
			steps{
				echo 'Code compilation and packaging'
				sh 'sleep 30'
			}
		}
	
		stage ("Test") {
			steps{
				echo 'Executing Test cases'
				sh 'sleep 40'
			}
		}
	}
}

  //SCRIPTED
  
  //	DECLARATIVE 
  pipeline  {
	agent any
	stages{ 
		stage('Build'){
			steps {
				echo "Build"
				}
			}	
			stage('Test'){
				steps {
					echo "Test"
				}
			}	
			stage('Integration Test'){
				steps {
					echo "Integration Test"
				}
			}	
		} 
		post {
			always{
				echo 'im awesome. i run always'
			}
			success{
				echo 'irun when success'
			}
			failure{
				echo 'i run when fail'
			}
		}
		
	}


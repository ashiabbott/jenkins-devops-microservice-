  //SCRIPTED
  
  //	DECLARATIVE 
  pipeline  {
	agent { docker {image 'maven:3.6.3'} }
	stages{ 
		stage('Build'){
			steps {
				sh 'mvn --version'
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


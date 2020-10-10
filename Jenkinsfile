pipeline{
  agent any
  stages{
		stage("Build Stage"){
			when{
				changelog 'Build'
			}
			steps{
				echo "Yes,change log contains build message..."
			}
		}
		stage("Deploy Stage"){
			when{
				changelog 'Deploy'
			}
			steps{
				echo 'This stage will use for Deploy'
			}
		}
	}
}

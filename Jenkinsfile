pipeline{
  agent any
  stages{
		stage("PerlFiles"){
			when {
				changeset '*.pl'
			}
			steps{
				echo "Yes, commit file contains perl files"
			}
		}
		stage("Java"){
			when{
				changeset '*.java'
			}
			steps{
				echo "Yes,commit files contain Java files"
			}
		}
	}
}
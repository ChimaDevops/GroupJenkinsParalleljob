pipeline{
	agent any
	stages{
		stage('parallel-level'){
			parallel{
				stage('sub-job1'){
					steps{
						echo "sub-job1 tasks and commands and actions"
					}
				}
				stage('sub-job2'){
					steps{
						echo "sub-job2 tasks and commands and actions"
					}
				}
			}
		}
		stage('version-check'){
			steps{
				echo "end of parallel job"
			}
		}
	}	
}
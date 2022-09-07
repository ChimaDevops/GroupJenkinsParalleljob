pipeline{
	agent any
	stages{
		stage('parallel-level1'){
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
        stage('parallel-leve2'){
			parallel{
				stage('sub-job3'){
					steps{
						echo "sub-job3 tasks and commands and actions"
					}
				}
				stage('sub-job4'){
					steps{
						echo "sub-job4 tasks and commands and actions"
					}
				}
			}
		}
        stage('parallel-level3'){
			parallel{
				stage('sub-job5'){
					steps{
						echo "sub-job5 tasks and commands and actions"
					}
				}
				stage('sub-job6'){
					steps{
						echo "sub-job6 tasks and commands and actions"
					}
				}
			}
		}
        stage('parallel-level4'){
			parallel{
				stage('sub-job7'){
					steps{
						echo "sub-job7 tasks and commands and actions"
					}
				}
				stage('sub-job8'){
					steps{
						echo "sub-job8 tasks and commands and actions"
					}
				}
			}
		}
		stage('status'){
			steps{
				echo "end of parallel job"
			}
		}
	}	
}
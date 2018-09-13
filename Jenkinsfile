pipeline{
	agent{
		node{ label 'python' }
	}
	stages{
		stage( 'python print version' ){
			steps{
				container('python'){ sh 'python --version'}
			}
		}
		stage( 'python print help’ ){
			steps{
				container('python'){ sh 'python --help'}
			}
		}
	}
}

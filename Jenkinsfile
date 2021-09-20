pipeline{  
  agent any
  stages{
    stage ('compile'){
	  steps{
	    sh ''' pwd
	    echo "compile"
	    '''
	  }
	}
	stage ('test'){
	  steps{
	    sh ''' whoami
		echo "test"
	    '''
	  }
	}
	stage ('install'){
	  steps{
	    echo "install"
	    echo "hello world"
	  }
	}
  }
}

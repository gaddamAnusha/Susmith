pipeline{  
  agent any
  stages{
    stage ('compile'){
	  steps{
	    pwd
		echo "compile"
	  }
	}
	stage ('test'){
	  steps{
	    whoami
		echo "test"
	  }
	}
	stage ('install'){
	  steps{
	    echo "install"
	  }
	}
  }
}

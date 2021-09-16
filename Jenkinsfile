 pipeline {
  
 agent any
  
  stages {
	stage("build"){
		steps {
		echo "build the app"
		}
	}

	stage("test"){
		steps{
		echo "test the app"
		}
	}


    stage("deploy"){
	     agent {
     		 label "windows"
    		 }
		steps {
			bat 'py pythonscript/hello.py'	
		}
	}
  }
}

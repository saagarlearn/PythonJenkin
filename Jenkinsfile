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
		steps{
		echo "deploy the app"
		 sh "#!/bin/bash \n" + 
       		 "chmod u+x pythonscript/hello.py" 
		 echo "The permission done"
		
		}
	}
  }
}

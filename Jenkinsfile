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
		steps {
        		sh "chmod +x -R ${env.WORKSPACE}"
        		sh '#!/bin/bash\n'+ 
			 './pythonscript/hello.py'    		
		}
	}
  }
}

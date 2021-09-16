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
        		sh "#!/usr/bin/python\n"+ 
			 "python ./pythonscript/hello.py"  		
		}
	}
  }
}

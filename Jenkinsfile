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
		sh 'chmod u+x pythonscript/hello.py'
		sh "#!/usr/bin/python" + 
		"pythonscript/hello.py"
		
		}
	}
  }
}

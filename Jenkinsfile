 pipeline {
  
 agent any
  stages {
	stage("build"){
		steps {
		sh 'echo "build the app"'
		}
	}

	stage("test"){
		steps{
		sh 'echo "test the app"'
	        sh 'echo "calling python"'
	        sh 'python ./pythonscript/hello.py'
		}
	}
  }
}

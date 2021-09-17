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
	        sh 'python ./pythonscript/hello.py'
		}
	}
  }
}

 pipeline {
  
 agent {
        docker { image 'python' }
    }
  
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
		sh """python pythonscript/hello.py"""
		
		}
	}
  }
}

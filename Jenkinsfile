pipeline {
  
  agent any
  
  stages {
	stage("build"){
		steps {
		echo "build the app"
		}
	}
  }
  stages {
	stage("test"){
		steps{
		echo "test the app"
		}
	}
  }
  stages {
    stages("deploy"){
		steps{
      echo "deploy the app"
		}
	}
  }
}

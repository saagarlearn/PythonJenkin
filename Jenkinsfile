 pipeline {
  
 agent { 
		 docker { 
			 image 'python:3.5.1' 
		 } 
 }
  stages {
	 stage("Env Variables"){
            steps{
                sh 'printenv'                                                     
            }
        }
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
			echo "deploy the app"
		}
	}
  }
}

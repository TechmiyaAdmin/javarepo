pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo 'build started'
		git 'https://github.com/TechmiyaAdmin/javarepo.git'
            }
	}
	stgae ('deploy'){
	    steps{
		echo "deploy"
            }
	}
	stage ('test'){
	    steps{
		echo "test"	       
            }
	}
    }
}

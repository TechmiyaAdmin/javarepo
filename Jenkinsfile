pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'build started'
		git branch: 'main', url: 'https://github.com/TechmiyaAdmin/javarepo.git'
            }
	}
	stage('deploy') {
	    steps {
		echo "deploy"
            }
	}
	stage('test') {
	    steps {
		echo "test"	       
            }
	}
    }
}

pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {   
		    script{
			    sh 'cd /home/resolve/Documents/Resolve_v7.2.0.11'
                	    def imageResult = docker.build("resolve-setu")
		    }	
            }
        }
    }
}

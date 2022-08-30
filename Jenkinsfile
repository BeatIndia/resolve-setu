pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {   
		    script{
                	    def imageResult = docker.build("resolve-setu", "/home/resolve/Documents/Resolve_v7.2.0.11")
		    }	
            }
        }
    }
}

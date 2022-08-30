pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {   
		    script{
                	    def imageResult = docker.build("resolve-main:7.2.0.11", "/home/resolve/Documents/Resolve_v7.2.0.11")
		    }	
            }
        }
    }
}

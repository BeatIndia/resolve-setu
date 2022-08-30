pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {   
		    script{
			    def dockerHome = tool 'docker'
        		    env.PATH = "${dockerHome}/bin:${env.PATH}"
			    sh 'cd /tmp/resolve-main/Resolve_v7.2.0.11'
                	    def imageResult = docker.build("resolve-main:7.2.0.11", "/tmp/resolve-main/Resolve_v7.2.0.11")
		    }	
            }
        }
    }
}

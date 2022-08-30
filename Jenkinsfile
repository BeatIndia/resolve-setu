pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {
		step{    
			sh 'cd /home/resolve/Documents/Resolve_v7.2.0.11'
                	imageResult = docker.build("resolve-setu", "/home/resolve/Documents")
		}	
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Building Resolve Image') {
            steps {   
			sh 'cd /home/resolve/Documents/Resolve_v7.2.0.11'
                	docker.build("resolve-setu", "/home/resolve/Documents")	
            }
        }
    }
}

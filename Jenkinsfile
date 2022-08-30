pipeline {
    agent any
	environment{
		def imageResult = ''
	}
    stages {
        stage('Building Resolve Image') {
            steps {
		sh 'cd /home/resolve/Documents/Resolve_v7.2.0.11'
		sh 'ls -latr'
                imageResult = docker.build("resolve-setu", "/home/resolve/Documents")
            }
        }
    }
}

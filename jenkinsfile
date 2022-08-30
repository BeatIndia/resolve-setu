pipeline {
    agent any

    stages {
        stage('Building Resolve Image') {
            steps {
		sh 'cd /home/resolve/Documents/Resolve_v7.2.0.11'
		sh 'ls -latr'
                def imageResult = docker.build("resolve-setu", "/home/resolve/Documents")
            }
        }
    }
}

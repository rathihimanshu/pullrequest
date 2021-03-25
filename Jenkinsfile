pipeline {
    agent any
    stages {
        stage('clonethecode') {
            steps {
                git 'https://github.com/rathihimanshu/pullrequest'

                sh "chmod +x script.sh"
                sh "./script.sh"
            }
        }
	stage('just a hello') {
	    steps {
		sh 'echo hello'
            }
	}
    }
}


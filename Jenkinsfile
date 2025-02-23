pipeline {
    agent any

    options {
        ansiColor('xterm')
    }

    stages {
    	stage("Update GIT Deployment") {
			steps {
				script {
					sh """
          ls
          """
				}
			}
	    }
    }

    post {
        always {
            cleanWs()
        }
    }
}

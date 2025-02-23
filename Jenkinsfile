pipeline {
    agent any

    options {
        ansiColor('xterm')
    }

    stages {
    	stage("Test Webhook") {
			steps {
				script {
					sh """
          				ls
	      				echo "test"
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

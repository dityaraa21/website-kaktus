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
	      				echo "test lg2"
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

pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
	            sh 'make deps'
	            sh 'make test'
		    sh 'make test_cov'
		    sh 'make test_xunit'	
        	}
        }
    }
}

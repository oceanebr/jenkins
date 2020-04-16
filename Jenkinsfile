pipeline {
	agent {
		docker {
			image 'node:6-alpine'
<<<<<<< HEAD:jenkinsfile
=======
			
>>>>>>> 2286e34f91eb2e2be095e169cbb2e1a550506915:Jenkinsfile
		}
	}
	environment {
		CI = 'true'
	}

	stages {
		stage('Build') {
			steps {
				sh 'npm install'
			}
		}
		stage('Test') {
			steps {
				sh './jenkins/scripts/test.sh'
			}
		}
		
	}
<<<<<<< HEAD:jenkinsfile

}
=======
}
>>>>>>> 2286e34f91eb2e2be095e169cbb2e1a550506915:Jenkinsfile

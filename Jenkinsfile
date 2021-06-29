pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                parallel(
			    	a: {
				        echo "This is branch a"
				    },
				    b: {
				    	echo "This is branch b"
				    }
            }
        }
        stage('test') {
            steps {
                parallel(
			    	a: {
				        echo "This is branch a"
				    },
				    b: {
				    	echo "This is branch b"
				    }
            }
        }
        stage('deploy') {
            steps {
                parallel(
			    	a: {
				        echo "This is branch a"
				    },
				    b: {
				    	echo "This is branch b"
				    }
            }
        }
    }
}
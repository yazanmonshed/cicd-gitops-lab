pipeline {
    agent {
        label 'cicd-node'
    }
    environment {
	MY_VAR = 'Hello, World!'
	PATH = "${PATH}:${WORKSPACE}/bin" // Example of extending an existing variable
	
}
    stages {
        stage('Hello World') {
            steps {
                echo "hello world"
		sh 'sudo docker build .'
		sh '${env.BRANCH_NAME}'
            }
        }
    }
}


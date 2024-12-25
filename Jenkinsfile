pipeline {
    agent {
        label 'cicd-node'
    }
    stages {
        stage('Hello World') {
            steps {
                echo "hello world"
		sh 'cat /etc/os-release'
            }
        }
    }
}


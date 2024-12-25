pipeline {
    agent {
        label 'cicd-node'
    }
    stages {
        stage('Hello World') {
            steps {
                echo "hello world"
		cat /etc/os-release
            }
        }
    }
}


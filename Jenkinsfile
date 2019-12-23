pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
		    sudo yum install -y python-pip
		    pip --version
		    sudo yum install -y python-devel
		    sudo yum groupinstall 'development tools'
                '''
            }
        }
    }
}

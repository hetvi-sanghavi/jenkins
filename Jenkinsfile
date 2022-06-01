pipeline {
    agent { 
        dockerfile {
            dir 'C://ProgramData//Jenkins//.jenkins//workspace//FirstDocker//'
            filename 'Dockerfile'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}

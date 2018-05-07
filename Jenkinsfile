pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh '.circleci/run_docker_build.sh'
            }
        }
    }
}

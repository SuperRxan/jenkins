pipeline {
    agent  none 
    stages {
        stage('build') {
            steps {
                script {
                    node('master') {
                        echo "Build started "
                        echo "${WORKSPACE}"
                        executecommand commandname:"./test.sh"
                    }
                  }
            }
        }
    }
}

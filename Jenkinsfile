pipeline {
    agent  none 
    stages {
        stage('build') {
            steps {
                script {
                    node('master') {
                        echo "Build started "
                        echo "${WORKSPACE}"
                        sh "ls"
                    }
                  }
            }
        }
        
        stage('test') {
            steps {
                script {
                    node('master') {
                        echo "Test started "
                        echo "${WORKSPACE}"
                        sh "ls"
                    }
                  }
            }
        }
    
        stage('docker') {
            steps {
                script {
                    node('master') {
                        echo "Docker started "
                        echo "${WORKSPACE}"
                        sh "ls"
                    }
                  }
            }
        }
        
         stage('publish') {
            steps {
                script {
                    node('master') {
                        echo "Publish started "
                        echo "${WORKSPACE}"
                        sh "ls"
                    }
                  }
            }
        }
    }
}



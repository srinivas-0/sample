pipeline {
    agent any
    stages { 
        stage('checkout SCM') {
            steps {
              sh "https://github.com/srinivas-0/sample.git"
            }
        }
        stage('Build') {
          steps {
            sh "mvn clean install"
          }
        }
    }
}

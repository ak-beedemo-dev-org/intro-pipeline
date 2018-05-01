pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Abhaya'
  }
}
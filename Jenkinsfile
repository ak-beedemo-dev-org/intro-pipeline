pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Abhaya'
    TEST_USER = credentials('test-user')
  }
}
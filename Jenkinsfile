pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}
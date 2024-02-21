pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        echo 'running hello automation'
        sh 'python3 hello.py'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('FD18') {
          steps {
            echo 'Fedora 18 64 bits'
          }
        }
        stage('FD24') {
          steps {
            echo 'Fedora 24'
          }
        }
      }
    }
  }
}
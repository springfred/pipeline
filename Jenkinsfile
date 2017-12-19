pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "aaaa"'
            build 'aaaa'
          }
        }
        stage('test1') {
          steps {
            echo 'aaaaa'
          }
        }
      }
    }
  }
  environment {
    aa = '11'
  }
}
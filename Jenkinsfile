pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'echo "aaaa"'
        build 'aaaa'
      }
    }
  }
  environment {
    aa = '11'
  }
}
pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
        echo 'AAA'
      }
    }
    stage('') {
      steps {
        sh 'echo 2'
      }
    }
  }
  environment {
    plik = 'test'
  }
}
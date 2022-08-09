pipeline {
  agent any
  tools{
    go 'go_lang'
  }
  stages {
    stage('dev') {
      steps {
        bat 'go version'
      }
    }

  }
}

pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sh './deploy'
        sh 'node -v'
      }
    }
  }
}
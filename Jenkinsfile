pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        bat(script: 'sh test.sh', returnStatus: true)
      }
    }
  }
}
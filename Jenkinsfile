pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        bat(script: 'test.sh', returnStatus: true)
      }
    }
  }
}
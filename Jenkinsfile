pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sshCommand(command: 'sh test.sh')
      }
    }
  }
}
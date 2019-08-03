pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sshCommand(command: 'test', remote: 'echo "test"')
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sshCommand(command: 'ssh root@167.99.233.55', remote: '167.99.233.55', sudo: true)
      }
    }
  }
}
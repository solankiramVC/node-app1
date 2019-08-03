pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sh 'echo "test"'
        sh 'node -v'
        sshCommand(command: 'sh test.sh')
      }
    }
  }
}
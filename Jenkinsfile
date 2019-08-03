pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        sh '''echo "Hello World!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"'''
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        bat 'sh deploy.sh'
        sh '''#ba
cd C:\\Program Files\\Git\\bin 
sh.exe 
git --version'''
        sh 'node -v'
      }
    }
  }
}
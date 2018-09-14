pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/tronidale/Release1', branch: 'master', changelog: true, credentialsId: 'tronidale', poll: true)
      }
    }
  }
}
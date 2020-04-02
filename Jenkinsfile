pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'dir /p', returnStatus: true, returnStdout: true)
        bat(script: 'dir', returnStatus: true, returnStdout: true)
      }
    }

  }
}
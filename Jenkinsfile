pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building the static website'
        sh 'ls -la'
      }
    }

    stage('Archive') {
      steps {
        archiveArtifacts artifacts: '**/*', fingerprint: true
      }
    }
  }
}

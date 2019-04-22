pipeline {
  agent any
  stages {
    stage('fase 1') {
      steps {
        echo 'Fase 1 '
        sh 'docker build -t app:test .'
      }
    }
    stage('fase 2') {
      steps {
        echo 'fase 2'
      }
    }
  }
}
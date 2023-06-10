pipeline {
  agent any
  stages {
    stage('Cmaking') {
      steps {
        sh 'cmake .'
      }
    }

    stage('Making') {
      steps {
        sh 'make'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Cmaking') {
      steps {
        sh 'cd build'
        sh 'cmake ..'
      }
    }

    stage('Making') {
      steps {
        sh 'make'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Construir') {
      steps {
        sh 'echo hola'
        sh 'echo \'Descargando codigo\' sh \'rm -rf *\' checkout scm'
        sh 'echo \'compilando aplicacion\' sh \'mvn clean compile\''
      }
    }

    stage('Unitarias') {
      steps {
        sh 'echo Unitarias'
      }
    }

    stage('Frontend') {
      steps {
        sh 'echo Front'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo deploy'
      }
    }

  }
}
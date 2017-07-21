pipeline {
  agent any
  stages {
    stage('Hello world') {
      steps {
        echo 'Hello'
        sleep 4
      }
    }
    stage('Deploy to prod') {
      steps {
        input(message: 'Deploy to prod', ok: 'Deploy')
      }
    }
  }
}
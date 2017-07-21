pipeline {
  agent any
  stages {
    stage('Hello world') {
      steps {
        echo 'Hello'
        sleep 4
        input(message: 'Plress enter', ok: 'enter')
      }
    }
  }
}
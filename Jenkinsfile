pipeline {
  agent any

  stages {
    stage('jenkins') {
      steps {
        sh '''
          echo 1234 | root -S docker-compose up -d --build
          ls
        '''
      }
    }
  }
}

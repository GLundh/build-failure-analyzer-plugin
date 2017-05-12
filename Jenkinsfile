pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            echo 'test'
            
          },
          "build": {
            echo 'build'
            
          }
        )
      }
    }
  }
}
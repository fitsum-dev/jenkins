pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Hello it is me'
        sh '''
        "Hello $Name"
        '''
      }
    }

  }
  environment {
    name = 'fitsum'
  }
}

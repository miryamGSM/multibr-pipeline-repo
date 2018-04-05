pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        echo %GIT_COMMIT%
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}

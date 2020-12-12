pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'python time.py'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }

  }
}

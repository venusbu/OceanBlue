pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Successfully built'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing completed'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployed'
        echo 'Deployed'
      }
    }

  }
}
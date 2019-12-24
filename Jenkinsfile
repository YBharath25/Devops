pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'testing'
          }
        }

        stage('Build') {
          steps {
            echo 'for the Building Process'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying is Done'
      }
    }

  }
}
pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo 'Testing'
          }
        }

        stage('parallel') {
          steps {
            echo 'parallel'
          }
        }

      }
    }

  }
}
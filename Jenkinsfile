pipeline {
  agent any
  stages {
    stage('testing') {
      parallel {
        stage('testing') {
          steps {
            echo 'welcome'
          }
        }

        stage('dev') {
          steps {
            sh 'java -version'
          }
        }

      }
    }

    stage('prod') {
      steps {
        echo 'echo "bye"'
      }
    }

  }
}
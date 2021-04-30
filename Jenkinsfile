pipeline {
  agent any
  stages {
    stage('lint') {
      parallel {
        stage('lint') {
          steps {
            echo 'test'
          }
        }

        stage('yaml-lint') {
          steps {
            sh 'echo "Tell it to yamll int"'
          }
        }

      }
    }

  }
}
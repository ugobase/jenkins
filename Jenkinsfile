pipeline {
  agent any
  stages {
    stage('Test') {
      post {
        always {
          echo '========always========'
        }

        success {
          echo 'An execution was successful'
        }

        failure {
          echo 'An execution failed'
        }

      }
      steps {
        echo 'Hello World'
        sh 'ls -ltra'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Success'
      }
    }

  }
}
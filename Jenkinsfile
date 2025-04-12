pipeline {
    agent any

    stages {
        stage("Test") {
            steps {
                echo "Hello World"
            }
            post {
                always {
                    echo "========always========"
                }
                success {
                    echo "An execution was successful"
                }
                failure {
                    echo "An execution failed"
                }
            }
        }
    }
}


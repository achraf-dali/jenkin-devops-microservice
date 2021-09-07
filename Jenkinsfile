pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
         stage('test') {
             steps {
                echo "test"
             }
         }
         stage('Integration Test') {
             steps {
                echo "Integration Test"
             }        
         }
    }

     post {
        always {
            echo "awesome i run always"
        }
        success {
            echo "i run when you fail"
        }
        failure {
            echo "i run when you fail"
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Build') {
    		echo "Build"
        }
         stage('test') {
             echo "test"
         }
         stage('Integration Test') {
             echo "Integration Test"
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

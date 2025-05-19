pipeline {
    agent { 
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
                script{
                    sh """
                        echo "Hello, This is Build"
                        sandeep
                    """
                }
            }
        }
        stage('Test') {
            steps {
                script{
                    sh """
                    echo "Hello, This is Test"
                    """
                }
            }
        }
        stage('Deploy') {
            steps {
                script{
                    sh """
                    echo "Hello, This is Deploy"
                    """
                }
            }
        }
    }
}


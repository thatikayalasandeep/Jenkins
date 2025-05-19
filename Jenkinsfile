pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    sh """
                        echo "Hello, This is Build"
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


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
    post{
        always{
            echo 'I will always say Hello again!'
        }
        failure{
            echo 'Build not completed or Failed'
        }
        success{
            echo 'Build completed successfully'
        }
    }
}


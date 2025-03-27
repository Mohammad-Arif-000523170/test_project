pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '✅ Compiling application code...'
                sleep 2
                echo '✅ Build completed!'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Running automated tests...'
                sleep 2
                echo '✅ All tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploying application to staging environment...'
                sleep 2
                echo '✅ Deployment successful!'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Bulding app code...'
            }
        }
        
        stage('test') {
            steps {
                echo 'Testing app...'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'Success!'
                echo 'Deploying straight into production...'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            when {
                branch 'deploy'
            }
            steps {
                echo "In deploy branch !!!"
            }
        }

        stage('Build') {
            when {
                branch 'test'
            }
            steps {
                echo "In test branch"
            }
        }

        stage('Upload') {
            when {
                branch 'main'
            }
            steps {
                echo "In main branch"
            }
        }
    }
}

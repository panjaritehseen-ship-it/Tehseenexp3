pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running testsc...'
            }
        }

        stage('Run Application') {
            steps {
                echo 'Running application...'
                bat 'python app.py'
            }
        }
    }
}

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
                bat '"C:\\Users\\student\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" app.py'
            }
        }
    }
}

 pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                sh '/home/sana/flutter/bin/flutter pub get'
            }
        }

        stage('Test') {
            steps {
                sh '/home/sana/flutter/bin/flutter test'
            }
        }
    }
}
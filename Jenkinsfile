pipeline {
    agent any

    stages{
        stage('Hello') {
            steps {
                sh 'docker build -t millertyv/flask_app .'
            }
        }
    }
}
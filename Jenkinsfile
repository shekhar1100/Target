pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'git --version'
                bat 'git remote show origin'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'git remote set-url origin https//github.com/shekhar1100/DataTestEmpty.git'
                bat 'git push -u origin -all'
            }
        }
    }
}

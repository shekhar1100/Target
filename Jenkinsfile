pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
              //  bat 'git remote set-url origin https//github.com/shekhar1100/DataTestEmpty.git'
              //  bat 'git push -u origin --all'
             //   bat 'git remote rm origin'
                bat 'git remote add origin https://github.com/shekhar1100/DataTestEmpty.git'
                bat 'git push origin master'
             //   bat 'git branch -M master'
               // bat 'git push -u origin master'
            }
        }
    }
}

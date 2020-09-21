pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'git remote add JaniTest https://github.com/shekhar1100/JaniTest.git'
              //  bat 'git remote set-url origin https//github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote set-url origin https://github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote rm origin'
              //  bat 'git remote add origin https://github.com/shekhar1100/DataTestEmpty.git'
              //  bat 'git push origin master'
             //   bat 'git branch -M master'
               // bat 'git push -u origin master'
               // bat 'git push DataTestEmpty master'
                bat 'git checkout master '               
                bat 'git push JaniTest master:master' 
            }
        }
    }
}

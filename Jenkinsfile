pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
              //  bat 'git remote add origin2 https://github.com/shekhar1100/JaniTest1.git'
              //  bat 'git remote set-url origin https//github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote set-url origin https://github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote rm origin'
              //  bat 'git remote add origin https://github.com/shekhar1100/DataTestEmpty.git'
              //  bat 'git push origin master'
             //   bat 'git branch -M master'
               // bat 'git push -u origin master'
               // bat 'git push DataTestEmpty master'
             //   bat 'git config --global user.email "you@example.com"'
             //   bat 'git config --global user.name "Your Name'
               // bat 'git checkout master '     
               // bat 'git commit -m "Initial commit" '
             //   bat 'git push origin2 HEAD:master'
               // bat 'git push origin2 master:master' 
               // bat 'git push origin2 HEAD:refs/heads/master'
                
             //   bat 'git push origin "refs/remotes/origin1/*:refs/heads/*"'
                
               bat 'git remote add team https://github.com/shekhar1100/Android_Test.git'
                bat 'git remote add free https://github.com/shekhar1100/DataTestEmpty.git'
                bat 'git fetch team'
                bat 'git checkout -b master team/master'
                bat 'git fetch free'
                bat 'git merge free/master'
                bat 'git push team master'
                
            }
        }
    }
}

pipeline{
    agent any 
     stages{
        stage ("compile"){
          step{
              sh 'javac test.java'
          }
        }
        stage("run"){
            step{
                sh 'java Test'
            }
        }
     }
}
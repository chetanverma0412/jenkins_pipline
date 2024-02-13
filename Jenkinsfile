pipeline {
    agent any 

    stages { 
        stage('compile') { 
            steps { 
                bat 'javac test.java' 
            }
        }
        
        stage('run') { 
            steps { 
               bat 'java test' 
            }
        }
    }
    post{
        always{
            bat 'echo "always"'
        }
        success{
            bat 'echo "success"'
        }
        failure{
            bat 'echo "failure"'
        }
    }
}

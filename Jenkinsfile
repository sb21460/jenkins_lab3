pipeline{
    agent any
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-pipeline || true"
            }
        }
        stage("add some files"){
            steps{
                sh "touch ~/jenkins-pipeline/file1.txt"
                sh "ls -al"
            }
        }
        stage("print success"){
            steps{
                echo "Printed Successfully"
            }
        }
    }
}

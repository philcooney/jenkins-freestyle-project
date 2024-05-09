pipeline{

        agent any

        stages{

            stage('Make Folder'){

                steps{

                    sh "mkdir ~/jenkins-tutorial-test"

                }

            }
          
            stage('Make Files'){

                steps{

                    sh "touch 1.txt 2.txt 3.txt 4.txt 5.txt"

                }

            stage('Archive Files'){

                steps{

                    sh "zip exercise1.zip *.txt"

                }

            }

        }

}

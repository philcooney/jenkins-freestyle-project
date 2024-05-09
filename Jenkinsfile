pipeline{

        agent any

        stages{

            stage('Make Folder'){

                steps{

                    sh "mkdir ~/jenkins-tutorial-test || true"

                }

            }
          
            stage('Make Files'){ //

                steps{

                    sh "touch ~/jenkins-tutorial-test/1.txt 2.txt 3.txt 4.txt 5.txt"

                }
            }
            
	    stage('Archive Files'){ //

                steps{

                    sh "zip ~/jenkins-tutorial-test/exercise1.zip *.txt"

                }

            }

        }

}


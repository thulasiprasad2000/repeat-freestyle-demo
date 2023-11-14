pipeline{

        agent any

        stages{

            stage('Make Directory'){

                steps{
                    sh 'echo "Test change to Jenkinsfile"'
                    sh "mkdir ~/jenkins-tutorial-test"

                }

            }

            stage('Make Files'){

                steps{

                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"

                }

            }

        }

}
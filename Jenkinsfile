pipeline {

    agent any

    stages {

        stage('Build') {

            steps {

           echo "build" 
                sh "javac HelloWorld.java"

            }

        }

        stage('Test') {

            steps {

               echo "test"
                sh "java HelloWorld"

            }

        }

        stage('Deploy') {

            steps {

              echo "deploy"

            }

        }

    }

}

pipeline {
    agent any

    stages {
        stage('Display Java Version') {
            steps {
                sh 'java --version'
            }
        }
        
        stage('Compile Java Program') {
            steps {
                sh '''
                    cd java-hello-world
                    ls -la
                    javac HelloWorld.java
                    java HelloWorld
                '''

            }
        }
        /*stage('Run Java Program') {
            steps {
                sh 'cd java-hello-world'
                sh 'ls -la'
                sh 'java HelloWorld'
            }
        }*/
    }
}
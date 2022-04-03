pipeline {
        agent any
        stages{
            stage('build'){
                steps {
                    echo "Compling the java source code"
                    sh 'javac Hello.java

                }
            }
            stage('run') {
                steps {
                    echo "Running the compilied java code."
                    sh "java Hello"
                }
            }
        }
    }

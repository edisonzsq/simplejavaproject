
pipeline {
        agent any

        stages {  
            stage ("build") {
                tools {
                   jdk "jdk7"
                }
                steps {
                    sh 'java -version'
                    sh 'javac Main.java'
                    sh 'java Main'
                }
            }
       }
}
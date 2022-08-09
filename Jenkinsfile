pipeline {

     agent any
     stages {
        stage('Compilation') {
           steps {
              sh 'mvn clean compile'
           }
        }
        stage('Test') {
                      sh 'mvn test'
                }
        }
        stage('Deploy') {
                      sh 'mvn  deploy'
             }
        }
     }

}